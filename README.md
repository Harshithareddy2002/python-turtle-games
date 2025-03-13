
# Python Turtle Module Games

This repository contains three classic arcade-style games implemented using Python's Turtle module:

1. **Turtle Crossing Game** (Inspired by Frogger)
2. **Snake Game**
3. **Pong Game**

Each game is housed in a separate directory:
- `Turtle Crossing Game/`
- `Snake Game/`
- `Pong Game/`

These games provide a fun way to explore Python's Turtle graphics while reinforcing programming concepts such as object-oriented programming and event-driven interactions.

## Game Descriptions

### 1. Turtle Crossing Game
- The objective is to help the turtle cross a road filled with moving cars.
- The player controls the turtle using the **Up and Down arrow keys**.
- If the turtle reaches the other side, it scores a point, and the traffic speed increases.
- If the turtle collides with a car, the game ends with a "Game Over" message.
- Classes used: `Player`, `CarManager`, and `Scoreboard`.

#### How to Play
1. Navigate the turtle across the screen using the **arrow keys**.
2. Avoid getting hit by the cars.
3. Each successful crossing increases the game difficulty.

![Turtle-1](Turtle_Crossing_Game/Turtle-1.png)
![Turtle-2](Turtle_Crossing_Game/Turtle-2.png)  

#### Customization
- To adjust the speed increment of the traffic, modify the `MOVE_INCREMENT = 10` constant in the `CarManager` class.

---

### 2. Snake Game
- A classic snake game where the snake moves constantly and must eat food to grow.
- The player controls the snake using the **arrow keys**.
- The game ends if the snake collides with a wall or itself.
- The score and high score are displayed at the top of the screen.
- The high score is stored in `data.txt` and updated when a new high score is reached.
- Classes used: `Snake`, `Food`, and `Scoreboard`.
  
#### How to Play
1. Move the snake using **arrow keys**.
2. Eat the food to increase length and score points.
3. Avoid colliding with walls or the snake's own body.

![Snake-1](Snake_Game/Snake-1.png)
![Snake-2](Snake_Game/Snake-2.png)

#### Customization
- Modify the snake speed in the `move()` method inside `Snake.py`.

---

### 3. Pong Game
- A two-player Pong game where each player controls a paddle to bounce a ball.
- The right-side player uses **Up and Down arrow keys** to move.
- The left-side player uses **W and S keys** to move.
- The objective is to make your opponent miss the ball to score points.
- The game speeds up with each successful hit.
- Classes used: `Ball`, `Paddle`, and `Score`.

#### How to Play
1. **Right player**: Use **Up and Down arrow keys** to move the paddle.
2. **Left player**: Use **W and S keys** to move the paddle.
3. Hit the ball with your paddle to send it back toward your opponent.
4. If your opponent misses, you score a point.

![Pong](Pong_Game/Pong.png)   

---

## Getting Started

### Prerequisites
- Python 3.11+
- Turtle module (pre-installed in Python)

### Installation & Running the Games

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/python-turtle-games.git
   cd python-turtle-games
   ```

2. Navigate to the specific game folder:
   ```sh
   cd Turtle_Crossing_Game  # or Snake_Game, Pong_Game
   ```

3. Run the game:
   ```sh
   python main.py
   ```

---

## Author & Credits

- **Developed by:** K.Harshitha Reddy
- **Instructional Guidance by:** Dr. Angela Yu (Udemy 100 Days of Python Bootcamp)
- **Inspired by:** Classic arcade games like Frogger, Snake, and Pong.

---

Enjoy playing these games and experimenting with the Turtle module! Feel free to modify the code to enhance the gameplay.

