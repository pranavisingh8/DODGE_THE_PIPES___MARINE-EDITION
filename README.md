# Dodge the Pipes - Marine Edition:::::::::

**Table of Contents**
- [Introduction](#introduction)
- [Game Description](#game-description)
- [Prerequisites](#prerequisites)
- [Code Overview](#code-overview)
- [Algorithm](#algorithm)

## Introduction

Dodge the Pipes - Marine Edition is an endless game inspired by the popular Flappy Bird. Developed in Python using the PyGame library, this game puts you in control of a fish. Your objective is to guide the fish through gaps between industrial pipes, accumulating points for each successful pass. However, if the fish collides with any pipes, the game ends.

This project showcases the practical application of various programming concepts, including functions, loops, and conditions. It offers an engaging and user-friendly gaming experience with sound effects to enhance realism.

## Game Description

- **Objective:** Guide the fish through gaps between pipes to score points while avoiding collisions.

- **Controls:** Use the spacebar to make the fish swim higher.

- **Game Over:** The game ends when the fish collides with a pipe. Your score is recorded, and you can restart the game.

## Prerequisites:

Before running the game, ensure you have the following:

- **Python IDE:** You'll need Python IDLE or Visual Studio Code.

- **Required Modules:** Install the PyGame, Random, and Sys modules using the following command:

  ```
  pip install pygame
  ```

- **Operating System:** Windows 7 and above.

- **Hardware Requirements:** An Intel Core™ i3 or above processor and at least 4GB of RAM.

## Code Overview

The game code utilizes the PyGame library, including functions such as `colliderect()`, `.get_rect()`, and `.blit()`. Random numbers are generated for pipe positions using `random.choice()`. The `sys` module is used for various functions and interactions with the Python runtime environment.

The code is organized into functions to handle different game aspects, ensuring clarity and modularity.

## Algorithm

The game follows a structured algorithm:

1. Start the game.

2. Display "Get Ready" and "Press Space" messages.

3. Check if the game is active (GameActive is True).

4. If active, check if the user quits or presses a key to start.

   - If the user quits, exit the game.
   - If a key is pressed, initiate the game and necessary loops.

5. Collect points, move the fish and pipes, and check for collisions while `isalive` and `isstarted` are True.

6. Play the bubble sound while the fish is moving and the die sound on collision with any pipe.

7. On collision, reset the fish's position, update the high score, reset the initial score to 0, and display "Get Ready" and "Press Space" messages again.

8. If the user presses space, restart the game. If the user quits, exit the game window.

9. Stop the game.

Enjoy playing Dodge the Pipes - Marine Edition, and may you achieve the highest score!

## Output
<img width="426" alt="Screenshot 2023-09-18 005704" src="https://github.com/pranavisingh8/DODGE_THE_PIPES___MARINE-EDITION/assets/138822333/a40fbc7b-06f4-491c-911e-0b4d61048b8e">
