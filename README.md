# 🪨📄✂️ Rock, Paper, Scissors AI – Command Line Version

This is a simple command-line game where the player competes against an AI that learns and predicts moves based on your input history.

---

## 🎯 Features

- 🧠 AI learns your move patterns and tries to counter them
- 🎮 Command-line interface (no GUI required)
- 🔁 Loop to keep playing until you choose to quit
- 🧾 Scoreboard: Player Wins, AI Wins, and Draws

---

## 📂 Folder Structure

rock-paper-scissors-ai/
│
├── main.py # Entry point of the game
├── README.md # Project documentation
├── requirements.txt # (Optional, if you want to list deps)
└── src/
├── init.py
├── ai.py # AI logic to predict moves
└── game.py # Game logic and scoreboard
---

## ⚙️ Requirements

- Python 3.6 or above
- No external packages required (only standard library)

To check your Python version:
```bash
python --version
▶️ How to Run
Open your terminal or command prompt

Navigate to the project directory:

bash
Copy
Edit
cd rock-paper-scissors-ai
Run the game:

bash
Copy
Edit
python main.py
How the AI Works
In the first round, the AI chooses a move randomly.

From the second round onward, it:

Tracks your previous choices.

Finds the most frequently chosen move.

Picks a move that defeats your most frequent one.

This creates an illusion of intelligence where the AI tries to beat your pattern.
author: Varsha
# RockPaperScissors
