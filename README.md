# CS50-Scratch-Balloon-Balls-Game.

BalloonXBalls & Aim Trainer
A CS50x Project created with Scratch

 Project Description
This is an interactive arcade-style game developed as part of the CS50 Introduction to Computer Science course. The game challenges players to test their reflexes and precision by popping rising balloons and hitting a moving target before their ammunition runs out.

 Features
 
-Dynamic Scoring System: Tracks player performance in real-time.

-Ammunition Logic: Players start with 25 shots. The game concludes precisely when the ammo count reaches zero.

-Time Tracking: A built-in timer records how long it takes the player to deplete their shots, adding a competitive "speed-run" element.

-Randomization: Balloons spawn at random X-coordinates and move at varying speeds, while a special "Bonus Ball" teleports to new locations upon being hit.

-Game State Management: Utilizes advanced Scratch Broadcasts (start game, end game) to manage transitions between the playing state and the "Game Over" screen.

-Interactive UI: Includes a hand-drawn "Game Over" screen and a functional Restart button to allow for seamless replayability.

 How to Play
 
-Start: Click the green flag or the "RESTART" button to begin.

-Aim & Click: Use your mouse to click on the rising balloons or the pink target ball.

-Scoring: Each successful hit increases your Score and consumes one Shot.

-End Game: Once you reach 0 Shots, the game will stop, display your final score, and show your total time.

 Technical Implementation
 
-Variables: Used score, shots, speed, and time to manage game data.

-Loops: Implemented forever and repeat until blocks for continuous movement and condition checking.

-Conditionals: Used if-then-else logic to handle ammunition checks and sound effects (Pop vs Oops).

-Synchronization: Leveraged Broadcast messages to ensure all sprites (balloons, targets, and UI) hide and show at the correct moments.
