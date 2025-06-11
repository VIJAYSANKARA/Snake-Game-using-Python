# Snake-Game-using-Python
🐍 Snake Game using Python and Tkinter
This program is a classic Snake Game built using Python’s Tkinter GUI library. The player controls a growing snake that moves around a grid, consuming food to gain points. The game ends if the snake hits the wall or its own body.

🔧 Key Features and Functionality:
Grid-Based Gameplay: The game uses a 25×25 tile grid rendered via Tkinter’s Canvas.

Snake Movement: Controlled using arrow keys (Up, Down, Left, Right), the snake changes direction smoothly.

Food Spawning: Food appears at random grid locations. Eating it increases the snake's length and score.

Collision Detection: Game ends when the snake hits the wall or collides with itself.

Score Tracking: The score is displayed in real time and shown on the game over screen.

🧠 How it works:
A Tkinter window is created and centered on the screen.

The Tile class is used to track positions of the snake and food.

The draw() function handles movement, drawing, and game logic, using canvas.create_rectangle() for visuals.

move() updates the snake’s body and position while checking for collisions.

The game loop refreshes every 100 milliseconds using window.after().

Arrow key presses are handled by change_direction() to set the snake's movement direction.

The game ends when the snake hits a wall or itself, and the score is shown on the screen.
