Drone Navigation Game

Welcome to the **Drone Navigation Game, a fun and interactive game where you guide a drone through a grid to reach its target while avoiding obstacles. Designed using Python's `turtle` module, this game is perfect for beginner coders exploring simple graphics and game mechanics.

Features

* A dynamic 5x5 grid-based gameboard.
* Interactive drone navigation using keyboard arrow keys.
* Randomly positioned target and obstacles after each successful target reach.
* Simple and engaging gameplay with a clean user interface.
* Built entirely with Python's built-in libraries, making it lightweight and easy to run.

How to Play

1. Use the arrow keys (`Up`, `Down`, `Left`, `Right`) to move the drone.
2. Navigate the drone to the green circle (`Target`) while avoiding red triangles (`Obstacles`).
3. When the drone reaches the target:

   * The target's position changes randomly.
   * Obstacles are cleared and repositioned randomly on the grid.
4. Avoid hitting the obstacles! If you do, the game ends.

Setup Instructions

Prerequisites

Python 3.x installed on your system.

Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/drone-navigation-game.git
   ```
2. Navigate to the project directory:

   ```bash
   cd drone-navigation-game
   ```
3. Run the game:

   ```bash
   python drone_game.py
   ```



Demo

Gameplay Example

> Navigate the drone through a maze of obstacles and reach your goal!

Code Highlights

1. Grid Creation
   The grid is dynamically drawn using the `turtle` module, ensuring scalability and reusability.

2. Randomized Challenges

   * The target (`green circle`) and obstacles (`red triangles`) reposition dynamically after each success, keeping the gameplay fresh.

3. Keyboard Controls
   Player inputs are seamlessly captured via Python's `onkey` event bindings.

Future Enhancements

* Add a scoring system to track successful attempts.
* Include a timer to increase gameplay intensity.
* Multiple levels with increasing grid size and obstacles.
* Dynamic messages for win/lose scenarios displayed on-screen.

Contributing

Contributions are welcome! If you have ideas for new features or optimizations, feel free to fork the repository, make changes, and submit a pull request.

License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Acknowledgments

* Built using the **Python Turtle Module**.
* Inspired by grid-based logic puzzles and drone navigation challenges.

