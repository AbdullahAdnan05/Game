# Alien Invasion 🚀👾

A classic 2D arcade shooter game built entirely in Python using the Pygame library. This project serves as a practical implementation of Object-Oriented Programming (OOP) principles, demonstrating class management, state tracking, and modular code design.

## Features
* **Dynamic Fleet Generation:** Aliens automatically populate the screen in rows and columns based on screen resolution.
* **Collision Detection:** Accurate sprite-based collision tracking between bullets and aliens, as well as the alien fleet and the player's ship.
* **Progressive Difficulty:** The game automatically increases in speed and difficulty as the player clears levels.
* **Scoring System:** Tracks current score, highest score, current level, and remaining lives (ships).
* **State Management:** Includes a Start menu, active gameplay state, and Game Over conditions.

## OOP Concepts Demonstrated
* **Encapsulation:** Game entities (Ship, Alien, Bullet, Scoreboard) are encapsulated into their own classes and separate files, managing their own behavior and data.
* **Inheritance:** Leverages `pygame.sprite.Sprite` to manage groupings and mass updates for bullets and aliens.
* **Modularity:** Global settings and game statistics are isolated in `Settings` and `GameStats` classes, making the game easy to tweak and balance without touching the core game loop.

## Prerequisites
To run this game, you will need Python installed on your machine along with the Pygame library.

## Installation & Setup

**1. Clone the repository:**
```bash
git clone [https://github.com/AbdullahAdnan05/Game.git](https://github.com/AbdullahAdnan05/Game.git)
cd Game
