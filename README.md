# Snake Game - C# Windows Forms

**Snake Game** is a classic game where the player controls a snake that moves around a field and grows each time it eats food. The goal is to avoid collisions with the wall or the snake's body and achieve the highest score.

This project is implemented in **C#** using **Windows Forms**, and contains additional features for managing scores and customizing the game.

---

## Main functionalities:

- **Snake movement**: Use the arrow keys to move in all four directions.
- **Random food**: Food appears at different positions on the field and grows the snake when caught.
- **Collision control**: The game stops if the snake collides with its own body; the walls are teleporters to avoid getting stuck.
- **Score and Highscore**: The current score is displayed during the game, and the highest score is automatically saved and updated.
- **Saving scores**: The scores can be saved to a text file and are sorted with **QuickSort**.
- **Undo (Unsave)**: The last saved scores can be removed from the file and array via an “Unsave” button.
- **Snake with different colors**: The snake’s head is black, while the body is dark blue; food is displayed in dark red.

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
