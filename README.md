# C++ Battleship Game

A robust, console-based recreation of the classic naval strategy game Battleship. [cite_start]This project demonstrates advanced C++ Object-Oriented Programming (OOP) concepts, featuring a custom game engine, smart AI opponents, and a modular architecture[cite: 14, 28].

## 🎮 Game Features

* [cite_start]**Tactical Gameplay:** Play on a classic 8x8 grid battlefield[cite: 15].
* **Game Modes:**
    * **Player vs CPU:** Test your skills against the computer.
    * **Smart AI:** The CPU features two difficulty levels. [cite_start]"Normal" mode fires randomly, while "Smart" mode utilizes adjacency targeting logic to hunt down ships after a hit[cite: 24, 30].
    * [cite_start]**Quickplay Demo:** A demonstration mode where the CPU plays against itself to showcase mechanics[cite: 24].
* [cite_start]**Ship Placement:** Choose between strategic **Manual Placement** or instant **Random Placement**[cite: 23].
* [cite_start]**Console UI:** A text-based interface featuring a command-center aesthetic, clear hit/miss indicators, and game logos[cite: 19, 51].

## 🛠️ Technical Architecture

[cite_start]The project is built using a modular approach to ensure extensibility and maintainability[cite: 28]. Key modules include:

* [cite_start]**Game Module:** Orchestrates the main loop, menu navigation, and state management[cite: 46].
* [cite_start]**Board Module:** Manages the 8x8 grid, validating ship placement and tracking cell states (Empty, Hit, Miss)[cite: 44].
* [cite_start]**Player Module:** Encapsulates logic for both Human and CPU players, managing their own board and their tracking board[cite: 40].
* [cite_start]**UI Module:** Abstracts console I/O, rendering the game board and handling user input[cite: 50].

## 🚀 Getting Started

### Prerequisites
* A C++ compiler (GCC/G++ recommended).
* A terminal or command prompt.

### Compilation
Navigate to the project directory in your terminal and run the following command to compile the source files:

```bash
g++ main.cpp board.cpp game.cpp player.cpp -o battleship
