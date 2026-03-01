# Snake Game in C# Windows Forms

In **Snake Game**, the player controls a snake that moves around a field and grows each time it eats food. The objective is to avoid colliding with the walls or the snake's body while achieving the highest score possible.

This project is implemented in **C#** using **Windows Forms** and includes features for managing scores and customizing the game.

---

## Main functionalities:

- **Snake movement**: Use the arrow keys to move in all four directions.
- **Random food**: Food appears in different positions on the field and increases the size of the snake when caught.
- **Collision control**: The game stops if the snake collides with its own body. The walls act as teleporters to help you avoid getting stuck.
- **Score and High Score**: The current score is displayed during the game, and the highest score is automatically saved and updated.
- **Saving scores**: Scores can be saved to a text file and sorted using QuickSort.
- **Undo (UnSave)**: The last saved scores can be removed from the file and array via the "Unsave" button.
- **Snake with different colors**: The snake's head is black and its body is dark blue. Food is displayed in dark red.

---

## How to play:

1. Open the game in **Windows Forms Application**.
2. Click **Start Game** to start the game.
3. Use the arrow keys to control the snake.
4. Catch the food to grow the snake and earn points.
5. Avoid colliding with your body; walls teleport the snake to continue the game.
6. After the game is over, you can save the score with **Save Score** or remove it with **Unsave Score**.

---

## Technologies used:

- **C#** - Game logic and functionalities.
- **Windows Forms** - Visual interface for the game.
- **System.IO** - For saving and reading scores from file.
- **QuickSort** - For sorting the saved scores in descending order.

---

## Advanced functionalities:

- **Stack for scores**: Saved scores are also saved in a stack, enabling the “undo” operation.
- **Restart Game**: The game can be restarted from scratch by creating the snake and food in new positions.
- **Dynamic Max Width & Height**: The playing field adapts to the size of the PictureBox.

---

This project is a good example to learn:

- Managing lists and objects (`List<Circle>` for the snake)
- Handling keyboard events (`KeyDown`, `KeyUp`)
- Functions for storing and manipulating data in files
- Using logic for games in **C# Windows Forms**
