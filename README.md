<p align="center">

<img src="docs/logo_tic-tac-toe.png" alt="FocusWall" width="150"/>

<h1 align="center">Tic-Tac-Toe (C)</h1>

<h3 align="center">Console-Based Game with Structured Logic and Clean Architecture</h3>


![Language](https://img.shields.io/badge/Language-C-blue?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Console-lightgrey?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</p>

---

## 📋 Index

- [About the Project](#-about-the-project)
- [Objective](#-objective)
- [Features](#-features)
- [Game Rules](#-game-rules)
- [Architecture](#-architecture)
- [Project Structure](#-project-structure)
- [Compilation & Execution](#-compilation--execution)
- [Future Improvements](#-future-improvements)
- [License](#-license)

---

## 🎯 About the Project

This project implements the classic **Tic-Tac-Toe** game in C, focusing on:

- Logical structuring
- Clean function separation
- Input validation
- Efficient board manipulation

> The goal is not the game itself, but the demonstration of **fundamental programming discipline**.

---

## 🧠 Objective

Develop a robust console-based game while applying:

- Modular programming principles  
- Clear control flow  
- Defensive programming techniques  
- Readable and maintainable code  

---

## ✨ Features

### 🎮 Core Gameplay
- Two-player mode (Player vs Player)
- Turn-based system
- Real-time board updates

---

### 🛡️ Input Validation
- Prevent invalid positions
- Avoid overwriting moves
- Ensure numeric input correctness

---

### 🧩 Game Logic
- Win condition detection (rows, columns, diagonals)
- Draw detection
- Game reset capability

---

## 📜 Game Rules

- The game is played on a 3x3 grid  
- Players alternate turns (X and O)  
- The first to align 3 symbols wins  
- If all cells are filled with no winner → draw  

---

## 🏗️ Architecture

### Core Components

<p>
```bash id="arch-ttt"
Game Engine
├── Board Management
├── Input Handling
├── Game Loop
└── Win Checker ```bash

</p>
---

## Logical Flow

Initialize Board
   ↓
Game Loop
   ├── Display Board
   ├── Get Player Input
   ├── Validate Move
   ├── Update Board
   ├── Check Win / Draw
   ↓
End Game

## 📁 Project Structure

tictactoe/
├── src/
│   ├── main.c
│   ├── game.c
│   ├── game.h
│   ├── board.c
│   ├── board.h
│
├── include/
│   └── headers (optional)
│
├── docs/
│   └── diagrams (optional)
│
└── README.md

## ⚙️ Compilation & Execution

### Requirements

- GCC or any C compiler

### Compile

gcc src/*.c -o tictactoe

### run

./tictactoe

##🔮 Future Improvements
###⚡ Intermediate
 - Player vs AI (random moves)
 - Score tracking
-  Restart system without exiting
###🧠 Advanced
 - Minimax Algorithm (unbeatable AI)
 - Difficulty levels
 - Modular CLI interface
##🚀 Professional Level
 - Unit tests (CMocka / Unity)
 - Makefile
 - Cross-platform build
 - Code coverage
##📄 License

MIT License

<div align="center">

Developed with structured logic and engineering discipline

</div>
