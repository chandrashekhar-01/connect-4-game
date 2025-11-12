# Connect 4 – Python AI Game

A Python-based implementation of the classic **Connect 4** game featuring an **AI opponent powered by Minimax with Alpha-Beta pruning**.  
The project uses **Matplotlib** for board visualization and allows human vs AI gameplay directly in the console.

---

## Project Overview

This project recreates the **Connect 4** board game on a 5x5 grid.  
The player competes against an **AI** that uses the **Minimax algorithm** to make optimal decisions by evaluating possible moves and outcomes.

**Key Features:**
-  **AI with Minimax + Alpha-Beta pruning**  
-  **Graphical board visualization** using Matplotlib  
-  **Player vs AI gameplay** in terminal  
-  **Dynamic heuristic scoring** and move evaluation  
-  **Fully implemented game loop** with winner detection  

---

## 🗂️ Folder Structure

```text
connect4_game/
│
├── connect4_game.ipynb       # Jupyter notebook containing full code
├── README.md                 # Project documentation
└── requirements.txt          # (Optional) Dependencies list
```

## 🕹️ How to Play

- The game starts with an **empty 5x5 board**.  
- You are **Player 1 (Blue)** — the AI is **Player 2 (Red)**.  
- On your turn, enter a **column number (0–4)** to drop your token.  
- The first player to align **four tokens** in a row, column, or diagonal wins.  
- The game ends when a player wins or the board becomes full (tie).

---

## 🧩 Game Logic Overview

- **Board Representation:** 2D list (5 rows × 5 columns)  
- **AI Decision Making:** Minimax algorithm with Alpha-Beta pruning  
- **Evaluation Function:** Heuristic scoring  
  - AI tokens = **+1**  
  - Player tokens = **-1**  
- **Winner Detection:** Checks horizontal, vertical, and both diagonal patterns  
- **Visualization:** Board rendered using **Matplotlib** (colored circles)

---

## 📈 Example Output

- The **console** prints the board matrix after each move.  
- The **graphical board** updates dynamically with colors:
  - 🟦 **Blue** → Player  
  - 🟥 **Red** → AI  

---

## 🔮 Future Improvements

- Add a **GUI interface** using Pygame or Tkinter  
- Implement **variable board sizes** (6×7 classical Connect 4)  
- Improve AI by enhancing heuristic evaluation  
- Add **score tracking**, restart option, and difficulty modes  

---

## 🧰 Technologies Used

- **Python 3**  
- **NumPy** – for array handling  
- **Matplotlib** – for board visualization  
- **Math** – Minimax logic, recursion, scoring  

---
## ⚙️ How to Run the Game

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/Connect4-Game.git
cd Connect4-Game
