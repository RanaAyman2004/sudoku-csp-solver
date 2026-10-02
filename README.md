# 🧩 Sudoku CSP Solver

A Python-based Sudoku solver developed as a team project for our Artificial Intelligence course.

The project models Sudoku as a Constraint Satisfaction Problem (CSP) and implements multiple solving techniques, including Backtracking Search, MRV, and the AC-3 Arc Consistency algorithm.

## ✨ Features

- Backtracking Search with MRV heuristic
- AC-3 Arc Consistency
- Hybrid AC-3 + Backtracking solver
- Auto-solve mode
- User input mode
- Playable Sudoku mode
- Conflict checking
- Animated solving visualization using Pygame

## 🧠 AI Concepts

- Constraint Satisfaction Problems (CSP)
- Backtracking Search
- Minimum Remaining Values (MRV)
- Arc Consistency
- AC-3 Algorithm
- Constraint Propagation

## 🛠️ Technologies

- Python 3
- Pygame

## 🎮 Modes

### 1. Backtracking (MRV)
Solves the Sudoku using backtracking while selecting the variable with the Minimum Remaining Values heuristic.

### 2. AC-3
Applies Arc Consistency to reduce the possible values of Sudoku cells before and during solving.

### 3. AC-3 + Backtracking
Combines constraint propagation using AC-3 with Backtracking to solve the puzzle.

👥 Team

This project was developed in collaboration with my amazing team:

    Rana Ayman

    Donia Abd Alhamed

    Esraa Ibrahem


## 🚀 Getting Started
1.  Clone the repo: (https://github.com/RanaAyman2004/sudoku-csp-solver.git)
2.  Install dependencies: `pip install pygame`
3.  Run the game: `python sud.py`
