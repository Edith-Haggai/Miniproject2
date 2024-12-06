Description
This is a simple, interactive clicker game created with HTML5, JavaScript, and WebGL. The goal of the game is to control falling balls and make them rise to higher levels by pressing the space bar. As you progress, the game introduces new levels with increasing difficulty. The game uses a yellow line to indicate level progression, and the timer counts down as you play. The game ends when the timer runs out, and you are shown a "Game Over" screen with your final level.

Features:
Start, pause, and resume game functionality
Multiple levels with increasing difficulty
Timer countdown
Ball movement and interaction with a yellow line
Game Over screen with final score
Key control support for various actions
Colorful, animated balls with random colors
Game Controls
Spacebar: Move the balls upwards.
P: Pause the game.
R: Resume the game after pausing.
Enter: Restart the game after losing.
Escape: Exit the game (closes the browser window).
Requirements
A modern web browser (Chrome, Firefox, Safari, Edge) that supports HTML5 and JavaScript.
How to Play
Start the Game: Press the "Start Game" button on the screen.
Game Mechanics:
Balls fall from the top, and you need to press the spacebar to make them rise.
The goal is to move the balls past the yellow line to progress through the levels.
As you progress through levels, the yellow line moves higher, and the time you have to play decreases.
Pause and Resume:
Press P to pause the game.
Press R to resume the game.
Restart the Game: After the game ends, press Enter to restart the game.
Features and Functionality
Level Progression: The game has 5 levels, each with different time durations:
Level 1: 3 seconds
Level 2: 4 seconds
Level 3: 5 seconds
Level 4: 7 seconds
Level 5: 8 seconds
The yellow line moves up with each level, requiring the player to act faster.
Once the player reaches the highest level, the game ends.
The game also shows a countdown timer to represent the remaining time.
Code Structure
HTML: The HTML structure sets up the canvas, buttons, and the "Game Over" screen.
CSS: Styles for the canvas and buttons, including some visual effects like a border and box-shadow.
JavaScript:
Handles game logic including ball movement, collision detection, level progression, timer management, and key event handling.
The game is rendered on the canvas, and the player interacts with the game using keyboard events.
Main Components:
Canvas: Displays the game, with a dynamic background, balls, and a yellow line indicating level progression.
Ball Class: Represents the balls, handles drawing and moving.
Game Functions: Includes functions for starting, pausing, and resetting the game, as well as level progression and game-over logic.
How to Run Locally
Download the game files to your local machine.
Open the index.html file in any modern web browser (Chrome, Firefox, Safari, Edge).
Enjoy the game!
Code Breakdown
Ball Class
Represents each ball in the game, with properties like position (x, y), size (radius), and color.
Includes methods to draw the ball and move it upwards when the spacebar is pressed.
Game Logic
Tracks the game's state, including whether it is running, paused, or over.
Updates the game time and checks if the player has reached the level threshold.
Draws the current level and remaining time on the canvas.
Handles keyboard inputs to pause, resume, restart, and exit the game.
Level Progression
As the balls cross the yellow line (which moves up with each level), the game progresses to the next level.
When the game reaches level 5, the game ends and a "Game Over" screen is displayed.
Timer
The game has a countdown timer that decreases every second.
The timer resets based on the current level, with shorter times as the levels progress.
Troubleshooting
Game Not Starting:
Ensure that JavaScript is enabled in your browser.
If the canvas does not load, try refreshing the page.
Balls Not Moving:
If the balls don't respond to spacebar presses, check if the browser's focus is on the game window. Ensure that the key events are being captured correctly.

