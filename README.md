# 🏆 Two-Player Chess Game
## 📌 PROJECT OVERVIEW
This project implements a two-player chess game in C++ using Object-Oriented Programming (OOP) principles.
The game includes move validation, special moves (castling, en passant, pawn promotion), and turn-based gameplay.
## 🚀 FEATURES
- ✅ Full chess mechanics with proper move validation
- ✅ Special Moves: Castling, En Passant, Pawn Promotion
- ✅ Move Logging with standard chess notation
- ✅ OOP Concepts Used:
- ✅ Abstraction (Base classes for pieces)
- ✅ Inheritance (Pawn, Rook, Knight, etc., inherit from a base class)
- ✅ Polymorphism (Virtual functions for move validation)
- ✅ Operator Overloading (++ operator for move counting)
- ✅ Exception Handling for invalid moves
## 🛠️ TECHNOLOGIES USED
- C++ (Standard Template Library - STL)
- OOP Principles
- Command-Line Interface (CLI) for gameplay

## 📂 PROJECT STRUCTURE
Explanation:
- `src/` contains all source code files
- `pieces/` contains separate classes for each chess piece
- `assets/` is for UI assets (if applicable)
- `README.md` contains documentation

/oop-chess-game
│── src/                  🔹 Main source code folder
│   ├── main.cpp          🔹 Entry point for the game
│   ├── board.cpp         🔹 Chessboard logic (handles moves)
│   ├── game.cpp          🔹 Core game logic (rules, turns, validations)
│   ├── pieces/           🔹 Separate classes for each piece
│   │   ├── piece.h       🟢 Base class (abstraction)
│   │   ├── pawn.cpp      ♙ Pawn behavior
│   │   ├── knight.cpp    ♘ Knight behavior
│   │   ├── bishop.cpp    ♗ Bishop behavior
│   │   ├── rook.cpp      ♖ Rook behavior
│   │   ├── queen.cpp     ♕ Queen behavior
│   │   ├── king.cpp      ♔ King behavior
│── assets/               🎨 UI assets (optional)
│── README.md             📜 Project documentation
│── LICENSE               📝 License file

## 🏗️ INSTALLATION & SETUP
 1️⃣ Clone the Repository
git clone https://github.com/yourusername/oop-chess-game.git
cd oop-chess-game

 2️⃣ Compile and Run the Game
g++ -o chess_game src/*.cpp -std=c++17
./chess_game

## 🎮 HOW TO PLAY
- Start the game and follow the on-screen instructions.
- Input moves using standard chess notation (e.g., E2 E4).
- The game enforces move validation, capturing, and check detection.
- Special moves like castling & en passant are automatically detected.

## 📜 GAME RULES & MECHANICS
1️⃣ Move Validation
- Ensures moves follow chess rules (e.g., pawns move forward, knights move in "L" shape).
2️⃣ Capturing Mechanism
- Opponent's pieces are removed upon valid capture.
3️⃣ Check & Checkmate Detection
- Prevents illegal moves that leave the king in check.
4️⃣ Special Moves
- Castling: Allows the king to move two squares toward a rook.
- En Passant: Special capture for pawns that move two squares forward.
- Pawn Promotion: Pawns reaching the last row can become a queen, rook, bishop, or knight.

## 👨‍💻 TEAM MEMBERS
- M. Prasanna Kumar (CS23B1011)
- Syed Farhan (CS23B2039)(Myself)
- Mohamed Amjad (CS23B2013)
- Barath Dharshan (CS23I1005)
- Aditya Lokesh (CS23I1029)

## ⭐ CONTRIBUTING & SUPPORT
- Fork the repository
- Report issues
- Submit pull requests
- If you like this project, leave a ⭐ on GitHub!

## 📌 UPLOADING TO GITHUB (STEP-BY-STEP)
1️⃣ Initialize Git
git init
git add .
git commit -m "Initial commit - Two-Player Chess Game"

2️⃣ Create a New Repository on GitHub
- Go to GitHub
- Click "New Repository"
- Set the name as "oop-chess-game"
- DO NOT initialize with a README (since we already have one)

3️⃣ Link Local Repo to GitHub
git branch -M main
git remote add origin https://github.com/yourusername/oop-chess-game.git

4️⃣ Push the Code
git push -u origin main

