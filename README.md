# 🐦 Flappy Plane Game

A 2D Flappy Bird-style arcade game built with **Python** and **Pygame**.  
The project recreates the classic gameplay mechanics including gravity-based movement, obstacle generation, collision detection, scoring, and animated sprites.

Players control a flying plane and must navigate through obstacles while avoiding collisions with the ground or pipes.

---

## 🎮 Features

- Real-time physics-based movement using gravity and velocity
- Random obstacle generation with adjustable spacing
- Continuous scrolling background and ground animation
- Sprite animation and rotation for realistic flight motion
- Accurate collision detection using sprite masks
- Score tracking based on survival time
- Game restart system with menu screen
- Sound effects and background music

---

## 🛠 Tech Stack

- **Python**
- **Pygame**

Concepts demonstrated:

- Object-Oriented Programming (OOP)
- Game loop architecture
- Sprite systems
- Collision detection
- Event-driven programming

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/flappy-bird-game.git
cd flappy-bird-game
```
### 2. Install dependencies
``` bash
pip install pygame
```
### 3. Run the game
```
python main.py
```
### 🎯 Controls
Jump / Fly : Mouse Click / space
Restart Game : Mouse Click after Game Over 

### ⚙️ Core Components
Sprites
- Implements animated game objects including:
- Player (plane)
- Background
- Ground
- Obstacles

Settings:
Stores global configuration such as window size and framerate.
