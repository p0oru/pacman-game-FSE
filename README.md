# Pac-Man Style Game

## Overview
This is a classic Pac-Man-inspired game where players control Pac-Man, navigating a maze, collecting food, and avoiding ghosts. Power-ups allow players to temporarily weaken ghosts, enabling Pac-Man to defeat them. The game features scoring, a leaderboard system, and win/loss conditions.

---

## Features
- **Classic Gameplay:** Collect food while avoiding ghosts.
- **Power-Ups:** Weaken ghosts to defeat them temporarily.
- **Dynamic Ghost Activation:** Ghosts are released gradually to increase difficulty.
- **Leaderboard:** Keeps track of the top 5 scores using local storage.
- **Pause and Play:** Toggle game state with a button for flexibility.
- **Win/Lose Conditions:**
  - Win: Collect all food items.
  - Lose: Collide with a ghost when it’s not weakened.

---

## How to Play
1. **Movement:**
   - Use arrow keys to move:
     - **Up Arrow:** Move up.
     - **Down Arrow:** Move down.
     - **Left Arrow:** Move left.
     - **Right Arrow:** Move right.
2. **Pause/Play:**
   - Click the **Pause Game** button to pause.
   - Click the **Play Game** button to resume.
3. **Winning:** Collect all food items to win.
4. **Losing:** Avoid colliding with active, non-weakened ghosts.

---

## Controls
- **Arrow Keys:**
  - Navigate Pac-Man in the maze.
- **Mouse:**
  - Toggle Pause/Play using the on-screen button.

---

## Scoring
- **Food:** Each food item collected earns 1 point.
- **Weakened Ghost:** Defeating a ghost while it’s weakened adds points and spawns a new ghost.

---

## Code Summary
### Key Files and Functions:
1. **Core Setup:**
   - `preload()`: Loads images for characters, food, and ghosts.
   - `setup()`: Initializes the game board, player, and objects.
2. **Gameplay Loop:**
   - `draw()`: Manages rendering, updates states, and handles collisions.
3. **Interactions:**
   - `keyPressed()`: Processes player movement.
   - `activateGhosts()`: Gradually releases ghosts into the maze.
   - `checkWin()`: Checks if all food is collected.
   - `gameOver()`: Handles the end-of-game logic.
4. **Leaderboard Management:**
   - `updateLeaderboard(score)`: Adds scores and keeps the top 5.
   - `displayLeaderboard()`: Displays the current leaderboard.
   - `resetLeaderboard()`: Clears the leaderboard data.

---

## Requirements
- **Environment:** Game developed using [p5.js](https://p5js.org/).
- **Assets:** 
  - Images for Pac-Man, food, ghosts, and power-ups are required in the `/images` folder.

---

## Installation
There isnt one just run the code on this link:
[p5.js](https://editor.p5js.org/killer1011/sketches/brd1ke60I)

---

Enjoy playing! 👾
