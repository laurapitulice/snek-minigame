# 🐍"Snek Minigame" - C++ Console Implementation

A classic Snake game built as a personal project during my first year of university. This project focuses on fundamental C++ concepts, memory management (arrays), and real-time console rendering.

## 🚀 Features
- **Non-blocking Input:** Uses `_kbhit()` and `_getch()` for real-time snake control.
- **Dynamic Tail Logic:** The snake grows as it consumes fruit, managed through coordinate arrays.
- **Score System:** Real-time score tracking displayed on the UI.
- **"Pacman" Mode:** The snake can pass through walls and reappear on the opposite side.

## 🛠️ Concepts Applied
- **Procedural Programming:** Logic organized into modular functions (`Setup`, `Draw`, `Input`, `Logic`).
- **Game Loop Architecture:** A continuous loop handling the update-render cycle.
- **Windows API:** Used `windows.h` for timing (`Sleep`) and console manipulation.
- **Coordinate Systems:** Managing 2D space using X and Y variables.

## 🎮 How to Play
1. **Download zip code and unzip file to the desired path**
2. **Open folder _snek_minigame_ in VSCode**
3. **Configure the compiler ("g++.exe"):**
    - in `launch.json`: set `"externalConsole": true`
    - in `tasks.json`: make sure the compiler used is `"g++.exe"`
4. **Run the program and play :)**
   
<img width="889" height="796" alt="Screenshot 2026-03-13 181914" src="https://github.com/user-attachments/assets/b5f6d147-42e4-4ff3-81ac-985fd3d960b5" />
