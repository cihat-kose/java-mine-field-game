
# Java Mine Field Game 🎮

**Java Mine Field Game** is a text-based, strategic mine-detection game implemented in Java. This game challenges players to navigate a grid full of hidden mines while avoiding detonations. Successfully uncover all safe spots to win!

---

## 🚧 Under Development

This project is currently in the development phase. Features and functionality may change as the game progresses. Contributions and feedback are welcome! If you're interested in contributing, please check the [How to Contribute](#how-to-contribute) section below. 🚀

---

## Features

- **Interactive Gameplay:** Fully text-based and runs in the console.
- **Customizable Grid:** Players can specify the size of the grid at the start.
- **Random Mine Placement:** Mines are randomly placed based on the grid size.
- **Dynamic Feedback:** The grid dynamically updates with the number of surrounding mines.
- **Win or Lose:** Avoid all mines to win, or hit one and lose the game.

---

## How to Play

1. Clone the repository:
   ```bash
   git clone https://github.com/cihat-kose/java-mine-field-game.git
   cd java-mine-field-game
   ```

2. Compile the game:
   ```bash
   javac -d bin ./src/_00_MineFieldGame/*.java
   ```

3. Run the game:
   ```bash
   java -cp bin _00_MineFieldGame.MineField
   ```

4. Enter the grid size (rows and columns).
5. Select a cell by entering the row and column indices.
6. Avoid mines and uncover all safe cells to win!

---

## Game Rules

1. The game runs on a two-dimensional grid.
2. Players specify the grid size (rows and columns).
3. Mines are randomly placed (1/4th of total cells).
4. Select a point by entering row and column numbers.
5. If the selected point contains a mine, the game ends.
6. If it's safe, the number of surrounding mines is displayed.
7. Clear all safe cells to win.

---

## Example Gameplay

```
Welcome to Mine Field Game!
Enter grid size (rows x columns): 4 4

Select a cell (row column): 2 3
Safe! 1 mine(s) nearby.

Select a cell (row column): 1 1
Oops! You hit a mine. Game Over!
```

---

## How to Contribute

Contributions are welcome!
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a Pull Request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contributors

- **Cihat Köse** – Initial Developer

---

## Project URL

[Java Mine Field Game Repository](https://github.com/cihat-kose/java-mine-field-game.git)
