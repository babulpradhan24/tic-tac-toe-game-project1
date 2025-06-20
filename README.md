# 🎮 Tic-Tac-Toe Console Game in Python

This is a simple command-line implementation of the classic Tic‑Tac‑Toe game built using Python. It supports a two-player mode (Player X vs Player O) and includes game state display, win checking, and draw detection.

## 🧠 Game Logic

- The game board is represented by two lists: one for Player X and one for Player O.
- Players take turns to input their moves.
- After every move, the program checks for:
  - A **win** (3 aligned symbols),
  - A **draw** (all cells filled with no winner).
- The game ends when a player wins or the board is full.

---

## 🖥️ Sample Output
Play Tic Tac Toe with me
0 | 1 | 2
--|---|--
3 | 4 | 5
--|---|--
6 | 7 | 8
X's chance
Please enter a value: 0

X | 1 | 2
--|---|--
3 | 4 | 5
--|---|--
6 | 7 | 8
O's chance
Please enter a value: 4

X | 1 | 2
--|---|--
3 | O | 5
--|---|--
6 | 7 | 8
X's chance
Please enter a value: 1

X | X | 2
--|---|--
3 | O | 5
--|---|--
6 | 7 | 8
O's chance
Please enter a value: 5

X | X | 2
--|---|--
3 | O | O
--|---|--
6 | 7 | 8
X's chance
Please enter a value: 2

X | X | X
--|---|--
3 | O | O
--|---|--
6 | 7 | 8
X won the match
Match Over!!!!!



