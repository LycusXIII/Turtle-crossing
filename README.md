**Turtle Crossing Game**

### **Project Description**

This Python project implements a Turtle corssing game where you control a turtle trying to safely cross a busy road. The goal is to reach the other side without getting hit by oncoming cars. As you progress, the cars move faster, making the game more challenging. If the turtle collides with a car, the game ends.

### **Getting Started**

1. **Prerequisites:**
   * Python 3.12 installed
   * `turtle` library (usually comes pre-installed with Python)

2. **Installation:**
   * Clone this repository or download the Python files (`main.py`, `car_manager.py`, `player.py`, `scoreboard.py`).

3. **Usage:**
   * Navigate to the project directory in your terminal.
   * Run the `main.py` file: `python main.py`

### **Gameplay**

* Use the (`Up`) arrow keys to move the turtle forwards.
* Avoid colliding with the oncoming cars traversing the road.
* Each successful crossing increases the level. The turtle returns to the starting position, and cars get faster.

### **Project Structure**

* **`main.py`:** Sets up the game window, creates the turtle, car manager, and scoreboard objects, and manages the game loop.
* **`car_manager.py`:** Handles car movements, including creating new cars, moving them across the screen, and increasing their speed as levels progress.
* **`player.py`:** Controls the player's turtle, enabling movement and checking if it reaches the finish line.
* **`scoreboard.py`:** Displays the current level and the "Game Over" message when the turtle collides with a car.

### **Dependencies**

This project relies on the `turtle` library, which is part of the standard Python library.

Link to the turtle documentation: https://docs.python.org/3/library/turtle.html

**Enjoy playing your Turtle Crossing Game!**
