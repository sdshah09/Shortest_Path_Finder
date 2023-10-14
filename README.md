# Maze Solver with Python and Curses

This is a Python program that solves a maze using a simple breadth-first search algorithm and displays the process in a terminal using the Curses library. It starts at the "O" (start) position and tries to find the path to "X" (end) while avoiding obstacles represented by "#" symbols.

## How to Run

1. Make sure you have Python installed on your system.

2. Clone this repository:

   ```
   git clone https://github.com/your-username/maze-solver.git
   ```

3. Navigate to the project directory:

   ```
   cd maze-solver
   ```

4. Run the program using the `wrapper`:

   ```
   python maze_solver.py
   ```

   The maze solver will start, and you'll see the process of finding the path from the start ("O") to the end ("X") in the terminal.

5. Press any key to exit the program after it finds the path.

## Maze Representation

The maze is represented as a 2D array in the code, with "#" representing walls and empty spaces representing valid paths. You can customize the maze by modifying the `maze` array in the `main` function.

## Dependencies

- Python 3.x
- [Curses](https://docs.python.org/3/library/curses.html) library (usually included with Python)

## Implementation Details

- The program uses a breadth-first search (BFS) algorithm to find the path from the start to the end in the maze.
- Curses library is used to visualize the process, with "X" marks indicating the path being explored and "O" representing the start.
