# Snake Game in Python

This is a simple Python game that features a snake navigating a screen to eat food and score points. The game includes multiple modules, each serving a specific purpose. The main functionality is implemented in the `main.py` file, while the game logic and features are divided into separate modules: `snake.py`, `food.py`, and `scoreboard.py`. The game's visual output is displayed using the `turtle` module.

## Files

### main.py

The `main.py` file serves as the entry point of the game. It initializes the game screen, sets up the snake, food, and scoreboard, and handles user input. The game loop continuously updates the screen, moves the snake, and checks for collisions with food, walls, and the snake's own tail.

### snake.py

The `snake.py` module contains the `Snake` class, which represents the snake controlled by the player. The snake is composed of segments (turtle objects), and the class provides methods to control its movement (up, down, left, right), extend its length when it eats food, and move the snake by updating the positions of its segments.

### food.py

The `food.py` module contains the `Food` class, responsible for managing the food items that the snake needs to eat. The `Food` class creates food items at random positions on the screen and provides a method to reposition the food once it has been eaten by the snake.

### scoreboard.py

The `scoreboard.py` module contains the `Scoreboard` class, which handles the game's scoring and display. It keeps track of the player's score and provides methods to increment the score when the snake eats food, as well as display the score and game over message when the game ends.

This modular organization allows for better code maintainability and separation of concerns.


## Usage

To play the Snake Game, follow these steps:

1. Ensure you have Python installed on your system.
2. Download or clone the project files to your local machine. 
3. Open a terminal or command prompt and navigate to the project directory. 
4. Run the following command to start the game:
``` python main.py ```
5. You can control the snake's movement using the arrow keys (up, down, left, right).
6. The goal is to guide the snake to eat as much food as possible without colliding with the walls or its own tail. 
7. The game ends when a collision occurs, and the score is displayed along with a game over message.


Feel free to explore and modify the code to enhance the game or add new features! Enjoy playing!