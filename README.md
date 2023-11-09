# A Simple Snake Game

This is a classic snake game with different difficulty levels where you control a snake to collect food and grow while avoiding or NOT avoiding collisions with the game boundaries and yourself. The game is built using HTML, CSS, JavaScript and [SweetAlert2](https://sweetalert2.github.io/) library.


## Logic Overview

- The game uses HTML tables to create a grid where the snake and food are displayed.

- The snake is represented as an array of cell coordinates, where each cell represents a segment of the snake's body.(number of ticks each snake cell stays active = length of the snake ) The player's directional input dynamically updates the snake's position. The game checks for collisions with grid boundaries and itself to determine if it's game over. When the snake consumes food, it appends a new cell to its array, effectively extending its length. 

- The JavaScript code handles game logic, including moving the snake, generating food, and checking for collisions.

- Different difficulty levels determine the snake's speed, the score required to level up, and the high score storage.

- For mobile users, on-screen buttons are provided to control the snake's direction.

- Added a toggle mechanism for wall collisions.

- The game provides feedback when a high score is achieved, encouraging players to improve their performance.

Have fun and enjoy playing SlitherQuest!