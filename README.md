# 🧩 Sudoku Solver 🎮

An **interactive visual Sudoku Solver** built with **Python** and **Pygame** that doesn't just solve puzzles—it lets you play, learn, and see how solving actually works, step-by-step! Whether you're a Sudoku enthusiast or someone curious about algorithms, this project brings logic to life.

---

## ✨ Features at a Glance

| Feature               | Description |
|------------------------|-------------|
| 🔄 **Random Puzzle Generator** | A fresh Sudoku board every time you run the game. |
| 🎨 **Visual Interface** | Click tiles, enter guesses, and interact in real time. |
| 🧠 **AI Solver (Backtracking)** | Watch the algorithm solve the puzzle cell by cell. |
| 💡 **Hint System** | Stuck? Press `H` and get a helpful nudge. |
| 🔢 **Keyboard Input** | Input values manually with instant feedback. |
| 🧱 **Built-in Validation** | Detects and highlights incorrect moves. |
| ⏳ **Timer & Mistake Counter** | Displays elapsed time and tracks errors. |

---

## 🖼️ Project Screenshots

> Add these images to the project directory and update paths accordingly.

### 🔷 Game Interface
<img width="688" height="792" alt="Screenshot 2025-08-07 123653" src="https://github.com/user-attachments/assets/a99e1e90-18cb-4409-8c60-4a36429c4066" />


### 🔷 Visual Solver in Action

<img width="698" height="812" alt="Screenshot 2025-08-07 123728" src="https://github.com/user-attachments/assets/9c0547bd-5330-4bb5-966d-65c0240633d2" />

---

## 🧠 How It Works

The project is built on **two core modules**:

### `sudoku.py` – The Game Engine
- Uses `pygame` to render a 9x9 board interactively.
- Tracks mouse clicks, key presses, and user interaction.
- Provides visual feedback (green = correct, red = wrong, gray = potential input).
- Solves the puzzle visually using a **recursive backtracking algorithm**.

### `sudokutools.py` – The Logic Brain
- Generates a valid and solvable Sudoku board.
- Implements all key algorithms: board validation, solving, and empty cell detection.
- Removes cells from the full board to create challenging puzzles.

---

## 📦 Setup Instructions

### 🔧 Prerequisites

Make sure you have Python 3 and Pygame installed. To install dependencies:

```bash
pip install pygame
```

### ▶️ Run the Game

```bash
python sudoku.py
```

---

## ⌨️ Controls

| Action            | Input              |
|-------------------|--------------------|
| Select Tile       | Mouse Click        |
| Insert Number     | Keys `1` to `9`    |
| Delete Entry      | `Backspace`/`Del`  |
| Submit Answer     | `Enter`            |
| Auto-Solve        | `Spacebar`         |
| Get a Hint        | `H`                |
| Quit Game         | Close Window       |

---

## 📁 Project Structure

```
sudoku-solver/
├── assets/
│   └── thumbnail.png          # Game window icon
├── images/
│   ├── game_ui.png            # UI screenshot
│   ├── visual_solver.gif      # Visual solving demo
│   └── hint_mode.png          # Hint feature image
├── sudoku.py                  # Main game engine (Pygame)
├── sudokutools.py             # Logic and board tools
└── README.md                  # You're here!
```

---

## 💬 Future Plans

- [ ] Add difficulty levels (Easy, Medium, Hard)
- [ ] Sound effects and UI animations
- [ ] Mobile-friendly layout
- [ ] Leaderboard with high scores

---
