# 🕹️ Console Pong Game in C++

A retro-style **2-Player Pong Game** built using **C++ and Win32 console APIs**. Players control vertical paddles to bounce a ball across the screen, competing to score 5 points first. The game includes a real-time interface, difficulty levels, keyboard input, score tracking, and win streaks.

---

## 🎮 Features

- **Two-Player Gameplay**
  - **Player 1 Controls:** `W` (up), `S` (down)
  - **Player 2 Controls:** `I` (up), `K` (down)

- **Game Mechanics**
  - Ball bounces off paddles and top/bottom walls
  - Score and winning streak tracking
  - First to 5 points wins the match
  - Option to restart after each match

- **Difficulty Levels**
  - Easy 🟢
  - Medium 🟡
  - Hard 🔴
  - Expert 🔥  
  *(Controls ball speed using `Sleep()` delay)*

- **Visual Display**
  - Custom boundary rendering using ASCII
  - Real-time paddle and ball movement using `gotoRowColumn()` (via `SetConsoleCursorPosition`)
  - Stats and player info printed in a separate zone

---

## 🧰 Technologies Used

- **Language:** C++
- **Platform:** Windows
- **Headers:**
  - `<Windows.h>` – Cursor control and screen manipulation
  - `<conio.h>` – Keyboard input handling (`_kbhit()`, `_getch()`)
  - `<ctime>` – (optional use for future enhancements like timing)

---

