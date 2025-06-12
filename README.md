# 🪨 Rock Paper Scissors AI 🎮

A Python command-line game where you play Rock, Paper, Scissors against a simple AI that learns and predicts your moves. The more you play, the smarter the AI gets!

---

## 📚 Table of Contents

- [🎯 About the Project](#-about-the-project)
- [✨ Features](#-features)
- [🎥 Demo](#-demo)
- [🛠 Technologies Used](#-technologies-used)
- [📊 Dataset](#-dataset)
- [⚙️ How It Works](#-how-it-works)
- [🚀 Running the Project](#-running-the-project)
- [🔭 Future Scope](#-future-scope)
- [👤 Author](#-author)

---

## 🎯 About the Project

This command-line game uses Python to simulate a Rock, Paper, Scissors match between the player and an AI. The AI analyzes the player's move history and makes strategic guesses to win. It helps demonstrate basic AI behavior, prediction patterns, and interaction loops.

---

## ✨ Features

- 🧠 **AI with Pattern Prediction:** AI chooses counter-moves based on the player's history.
- 🖥 **Command-line Interface:** Lightweight and easy to use.
- 📊 **Scoreboard:** Tracks wins, losses, and draws.
- 🔁 **Replay Support:** Play as many rounds as you like.
- 🧪 **Modular Codebase:** Organized using `ai.py`, `game.py`, and `main.py`.

---

## 🎥 Demo

Welcome to Rock, Paper, Scissors AI!
Enter move (rock/paper/scissors or 'quit'): rock
AI chose: paper
AI wins!
Score -> Player: 0, AI: 1, Draws: 0
Enter move (rock/paper/scissors or 'quit'): scissors
AI chose: rock
AI wins!
Score -> Player: 0, AI: 2, Draws: 0
Enter move (rock/paper/scissors or 'quit'): quit
Thanks for playing!
Final Score -> Player: 2, AI: 4, Draws: 1

yaml
Copy
Edit

---

## 🛠 Technologies Used

- **Language:** Python 3
- **Standard Libraries:** `random`, `input/output`

---

## 📊 Dataset

This project does **not use an external dataset**. It uses the player's own move history during the session as a dynamic internal dataset for predictions.

---

## ⚙️ How It Works

- First move: AI chooses randomly.
- From second move onward:
  - Tracks the most frequent move from player history.
  - Selects a move that beats the most common one.
- Example: If player often chooses 'rock', AI will likely choose 'paper'.

This behavior is encoded using a frequency-based decision model.

---

## 🚀 Running the Project

### ✅ Prerequisites

- Python 3.6 or higher installed on your system.

### ▶️ Steps to Run

1. **Clone the repository or download the code.**
2. **Navigate to the project directory.**
   ```bash
   cd rock-paper-scissors-ai
Run the game:

bash
Copy
Edit
python main.py
📁 Folder Structure
bash
Copy
Edit
rock-paper-scissors-ai/
├── main.py             # Main script to run the game
├── README.md           # Project documentation
└── src/
    ├── __init__.py
    ├── ai.py           # AI prediction logic
    └── game.py         # Game mechanics & scoreboard
🔭 Future Scope
✅ Add a GUI using tkinter or PyQt

✅ Include sound effects and images

🔁 Save and load game history from a file

📈 Improve AI with machine learning techniques

🌐 Deploy as a web version using Flask or Django

👤 Author
Varsha 
ravipativarshareddy@gmail.com
