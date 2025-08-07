🧩 Sudoku Solver (Pygame-Based)
This is an interactive Sudoku Solver built using Python and Pygame. It generates a random Sudoku puzzle, allows manual input from the user, provides hints, and features a visual solver using backtracking.

🚀 Features
🎲 Random Board Generation: Generates a new puzzle every time.

🧠 Backtracking Algorithm: Solves the board visually in real-time.

💡 Hint System: Automatically fills in a correct number.

⌨️ Keyboard Input: Enter your guesses and check correctness.

✅ Validation Feedback: Highlights correct and incorrect moves.

⏱️ Timer & Mistake Counter: Tracks time and wrong attempts.

🖱️ Mouse Interaction: Click tiles to select and edit.

🖼️ Demo
On running the project, a new Sudoku puzzle appears. Use keyboard numbers (1–9) to input guesses, and press Enter to confirm. Press H for a hint, or Space to auto-solve.

🧩 How It Works
sudoku.py: Main game interface using pygame. It handles board rendering, interaction, and visual solving.

sudokutools.py: Contains logic for generating boards, checking validity, and solving using backtracking.

🧪 Algorithms Used
Backtracking for solving the puzzle.

Randomized board generation by pre-filling diagonal 3x3 blocks and solving the rest recursively before removing cells.

🛠️ Requirements
Python 3.x

Pygame

Install dependencies with:

bash
Copy
Edit
pip install pygame
🕹️ Controls
Action	Key/Mouse
Select a Tile	Mouse Click
Input a Number	1–9
Delete Input	Backspace/Del
Confirm Input	Enter
Get a Hint	H
Auto Solve	Spacebar
Quit Game	Window Close

📂 File Structure
graphql
Copy
Edit
sudoku-solver/
├── assets/
│   └── thumbnail.png         # Game icon
├── sudoku.py                 # Main GUI and interaction logic
├── sudokutools.py            # Board generation and solving logic
└── README.md                 # Project documentation
🎮 How to Run
Clone or download this repository.

Make sure you have Pygame installed.

Run the main script:

bash
Copy
Edit
python sudoku.py
📌 Notes
The generate_board() function ensures each puzzle has a valid solution.

The game is meant for educational and demonstrative purposes. It does not include difficulty levels or puzzle validation beyond solvability.

🤖 Future Improvements
Add difficulty levels (Easy, Medium, Hard)

Timer-based scoring system

Mobile/Touch support

Sound effects

📜 License
This project is open-source and available under the MIT License.
