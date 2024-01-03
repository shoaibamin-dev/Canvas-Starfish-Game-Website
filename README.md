# Starfish-Crab-Game

This HTML canvas-based game, "Starfish eat Crab Game," involves controlling a starfish to eat crabs while avoiding collisions. The game consists of multiple tasks that need completion, and the code provides a structured framework for handling game mechanics.

## Tasks

1. **Arrow Key Movement (5 marks):**
   - Add an event listener to handle arrow keys for moving the starfish in all directions.

2. **Arrow Key Handling (15 marks):**
   - Complete the code in the event handler function to handle up, down, left, and right arrows for starfish movement.

3. **Starfish-Crab Interaction (35 marks):**
   - In the `moveStarfish()` function, complete the if statement to detect if the starfish is near the crab.
   - Update the crab eaten count, play an audio sound, and implement three conditions to level up.
   - Define your own values for the next level, crabs to eat count, and speed.

4. **Score Display (5 marks):**
   - Complete the code in the `displayScoreArea()` function to display the current level and crabs eaten score.

5. **General Note:**
   - Read the existing code carefully; there is no need to declare new functions and variables.

## Game Components

- **Canvas:**
  - The game canvas is identified as "canvas1" with a width of 400 and height of 200 pixels.

- **Images:**
  - Starfish and crab images are loaded into the game. The starfish starts near the center left, and the crab starts at a predefined position.

- **Variables:**
  - Various variables, such as crabsEaten, timeRemaining, level, crabsToBeEaten, and crabSpeed, are used to manage game state.

- **Audio:**
  - An audio file ("eating.wav") is played when the starfish eats a crab.

## Controls

- Arrow keys (UP, DOWN, LEFT, RIGHT) are used to control the starfish movement.

## Game Logic

- The game involves moving the starfish and detecting collisions with crabs.
- When a collision is detected, the crabs eaten count is updated, and the game may level up based on predefined conditions.
- The game includes a time limit and displays the current level and crabs eaten score.

## Execution

1. Open the HTML file in a web browser to play the game.
2. Use arrow keys to control the starfish.
3. Eat crabs, level up, and enjoy the game!

Feel free to explore and modify the code as needed. If you have any questions or need assistance, refer to the documentation within the code.
