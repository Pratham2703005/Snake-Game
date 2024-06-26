1. Objective: The goal of the game is to control a snake on a grid-based board. The snake moves continuously in a direction and grows in length whenever it eats food.

2. Movement: You control the snake's movement using the arrow keys (Up, Down, Left, Right). Each key press changes the snake's direction accordingly.

3. Game Elements:
- Snake: Initially consists of one segment. Grows longer with each food item eaten.
- Food: Appears randomly on the board. When the snake's head overlaps with food, it "eats" the food, grows longer, and the score increases.
- Score: Tracks the number of food items eaten.
- High Score: Keeps track of the highest score achieved, stored locally using localStorage.

4. Collision Detection:
- Self-collision: If the snake's head collides with any part of its body, the game ends.
  Wall collision: If the snake moves outside the boundaries of the board, the game ends.

5. Game Over:
- When the game ends due to collision, a game over sound plays, and the music pauses temporarily.
- An alert prompts the player to press any key to restart the game.

6. Sound Effects:Various sound effects enhance gameplay, including sounds for eating food, moving the snake, and game over.

7. Background Music: Continuous background music plays throughout the game, adding to the atmosphere.

8. Restarting the Game: Upon game over, pressing any key resets the game. The snake returns to its initial position, and gameplay resumes.

9. Responsive Design: The game adapts to different screen sizes (responsive design) due to its use of viewport settings and flexible grid layout.

10. Local Storage: Utilizes localStorage to store and retrieve the player's high score across different game sessions.
