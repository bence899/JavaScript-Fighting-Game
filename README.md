2D Fighting Game
Overview
This is a 2D fighting game built using JavaScript, HTML5 Canvas, and the GSAP animation library. The game features two fighters, each with their own set of animations, health bars, and attack mechanics. The objective is to reduce your opponent's health to zero or have more health remaining when the timer runs out.

Features
Dynamic Sprite Animations: Smooth and responsive animations for idle, running, jumping, falling, attacking, taking hits, and death sequences for both fighters.
Health Bars: Real-time health bar updates for both players, reflecting damage taken during the fight.
Timer: A countdown timer that determines the winner based on remaining health when time runs out.
Collision Detection: Precise collision detection that determines whether an attack lands successfully or misses.
Responsive Controls: Player 1 controls using WASD for movement and spacebar for attacks; Player 2 controls using arrow keys for movement and attack.
How to Play
Start the Game: Load the HTML file in a modern browser.
Controls:
Player 1:
Move Left: A
Move Right: D
Jump: W
Attack: Spacebar
Player 2:
Move Left: ←
Move Right: →
Jump: ↑
Attack: ↓
Objective:
Attack your opponent to reduce their health.
Avoid your opponent’s attacks to maintain your health.
The game ends when the timer runs out or when one player’s health reaches zero.
Project Structure
index.html: The main HTML file that sets up the game’s canvas and includes necessary scripts.
js/utils.js: Utility functions for collision detection and determining the winner.
js/classes.js: Definitions for the Sprite and Fighter classes, handling animations and game logic.
index.js: The core game logic, including animation loops, player controls, and event listeners.
img/: Contains all the sprite images for the background, fighters, and other assets used in the game.
Technologies Used
HTML5 Canvas: For rendering the 2D game environment and character animations.
JavaScript: Core game logic, animations, and interactivity.
GSAP: For smooth and efficient animation of health bars and other elements.
CSS: Basic styling for fonts and layout.
