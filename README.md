# Chess Game Engine in Python

This project implements a simple command-line Chess Game Engine using Python. It's designed to showcase fundamental object-oriented programming (OOP) principles, algorithmic thinking, and problem-solving skills through the core logic of chess.

---

## Project Poster

Here's a visual summary of the project:

![Chess_Engine Poster](https://github.com/alphaaa-m/Chess_Game_Engine/blob/main/Chess_Game-Cover.png)

---

## Features

* **8x8 Chess Board:** A dynamic representation of the chessboard.
* **Abstract Piece Class:** A foundational abstract class (`Piece`) defining common attributes and an `is_valid_move` interface.
* **Individual Piece Logic:** Subclasses for each chess piece (Pawn, Rook, Knight, Bishop, Queen, King), each with their unique movement validation rules.
* **Player Turn Management:** A system to alternate turns between two players (White and Black).
* **Move Validation:** Comprehensive checks for valid moves, including:
    * Ensuring the target position is on the board.
    * Preventing moves to the same starting position.
    * Blocking "friendly fire" (moving to a square occupied by your own piece).
    * Checking for obstacles along the path for Rook, Bishop, and Queen moves.

---

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/chess-engine.git](https://github.com/your-username/chess-engine.git) # Replace with your repo URL
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd chess-engine # Or whatever your project folder is named
    ```
3.  **Run the game:**
    ```bash
    python chess_game.py # Assuming your main game file is named chess_game.py
    ```

---

## How to Play

1.  The board will be displayed with the initial chess setup.
2.  The game will prompt the **current player** (White starts) to enter a **starting position** (e.g., `6,4` for row 6, column 4).
3.  Next, enter the **ending position** (e.g., `4,5`).
4.  The game will validate your move. If it's valid, the piece will move, and the turn will switch. If invalid, you'll be prompted to try again.
5.  Follow the on-screen prompts to continue playing.

---

## Project Structure

* `chess_game.py`: Contains the `ChessGame` class, `Board` class, `Player` class, and all `Piece` subclasses. (For larger projects, these might be split into separate files.)

---

## Learning Outcomes

This project significantly strengthened my understanding of:

* **Object-Oriented Design:** Applying principles like abstraction, inheritance, and polymorphism to a real-world problem.
* **Modular Programming:** Breaking down a complex system into smaller, manageable, and reusable components.
* **Algorithmic Thinking:** Developing and implementing precise rule sets for diverse piece movements.
* **Problem-Solving:** Systematically identifying and resolving logical challenges within the game's mechanics.

---

## Future Enhancements

* Check and Checkmate detection.
* Special moves: Castling, En Passant, and Pawn Promotion.
* Fifty-move rule and Threefold Repetition.
* Graphical User Interface (GUI) using libraries like Pygame or Tkinter.
* An AI opponent for single-player mode.

---

## Author

Muneeb Ashraf
* [LinkedIn](https://www.linkedin.com/in/muneeb-ashraf-3oo6275648/)
* [GitHub](https://github.com/alphaaa-m)

---
