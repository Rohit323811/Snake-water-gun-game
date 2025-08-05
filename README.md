# 🐍 Snake-Water-Gun Game in C

![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY--ND%204.0-lightgrey.svg)

A simple, fun console-based Snake-Water-Gun game written in pure C language — with a twist of randomness and scoring system!  
Built with ❤️ by **Rohit**.

---

## 🎮 How to Play

- Run the program
- Choose your move:
  - `1` for Snake
  - `2` for Water
  - `3` for Gun
- Computer randomly selects its move
- Rules:
  - Snake drinks Water 🐍💧 ➝ Snake wins
  - Water drowns Gun 💧🔫 ➝ Water wins
  - Gun shoots Snake 🔫🐍 ➝ Gun wins
- The game keeps score and tracks the high score from past games!

---

## 🛠️ Requirements

- Any C compiler (Turbo C / GCC / online compiler)
- Basic understanding of compiling `.c` files

---

## 📂 Files Included

- `snake_water_gun.c` – Main game logic
- `highscore.txt` – Stores and updates high score after each session
- `LICENSE` – Legal info about reuse

---

## 🔧 How to Compile (for beginners)

If you're using **GCC**:
```bash
gcc snake_water_gun.c -o swg
./swg
