# Maze-Runner
This project is a Maze Solver Application written in C++, which uses Depth-First Search (DFS) to find a path from a given starting point to a goal in a maze.

Key Features:
Maze Input: The maze is represented as a 2D grid where:
0 represents a path,
1 represents a wall,
2 represents the goal.
User Input: The user specifies the maze dimensions, the maze layout, and the starting point for solving the maze.
Path Finding Algorithm: The program utilizes Depth-First Search (DFS) to explore the maze and find a path from the starting position to the goal.
Maze Visualization: The maze is printed before and after solving. If a path is found, the path cells are marked with an asterisk (*) in the output.
Backtracking: If a path is not found, the algorithm backtracks, resetting explored cells to their original state.
Technologies Used:
C++: Implements the maze solver and handles input/output operations.
DFS Algorithm: Core algorithm used for solving the maze.
