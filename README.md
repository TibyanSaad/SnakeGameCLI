# SnakeGameCLI
##  Overview
A basic Snake game program in Java that handles movement, food spawning, growth, collisions, and saves the game state to files.
##  Features
- Snake movement in four directions: **Up, Down, Left, Right**
- **Edge wrapping**: snake reappears on the opposite side when crossing boundaries
- **Food spawning** (`+`) at random positions, avoiding the snake’s body
- **Growth mechanic**: snake grows when eating food
- **Collision detection**: prevents invalid moves and detects body collisions
- **Persistent game state**: saves map and snake coordinates to files
- **Console display**: prints the map and snake’s position with animation delay

##  File Structure
- `map.txt` → Stores the current game map
- `snakeCoordinates.txt` → Tracks snake’s body positions
- `MoveSnake.java` → Main game logic

## How to Run (Windows CMD)
1. Open Command Prompt and navigate to the folder containing your files:
   ```cmd
   cd C:\Users\YourName\SnakeGame\src
2. Compile the program:
   ```cmd
   javac MoveSnake.java
3. Run the program with a direction (and optional steps (deafualt is 1)):
   ```cmd
   java MoveSnake up
   java MoveSnake right 3

## Valid Movement
- Up
- Down
- Left
- Right 
