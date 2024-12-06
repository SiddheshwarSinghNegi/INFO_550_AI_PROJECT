# INFO_550_AI_Search_Games_Project
This project implements and compares AI search algorithms—BFS, DFS, A*, and Bidirectional Search—across three games: Maze Solver, 8-Puzzle, and String Transformation.
Each game presents unique challenges in state-space search, enabling us to study and evaluate the performance of BFS (Breadth-First Search), DFS (Depth-First Search), A Search*, and Bidirectional Search. The goal is to explore the efficiency of these algorithms in terms of time and space complexity, and to visually represent their behavior through an interactive graphical user interface (GUI).

The project is designed in response to the professor's feedback, with the following adjustments:

Random Agents: Added functionality to randomize the initial state of each game to generate different problem configurations.
Visualization: Smooth animations showing the search process, providing insights into how algorithms explore the state space.
Performance Metrics: Time taken and space utilized are displayed for each algorithm to help users compare their efficiency.
Games Implemented:
Maze Solver

The maze is generated randomly, with walls and a clear path from the start (green) to the goal (red).
Users can solve the maze using different algorithms. Each solution is visualized with a step-by-step animation.
Algorithms Implemented: BFS, DFS, A*, and Bidirectional Search.
8-Puzzle Game

A classic sliding tile puzzle where the user arranges numbered tiles from 1 to 8 in the correct order by moving the empty space (0).
Randomized initial states are generated to ensure variability.
Algorithms Implemented: BFS, DFS, A*, and Bidirectional Search. A warning is displayed when using DFS due to potential long execution times for complex configurations.
String Transformation Game

The objective is to transform a start word (e.g., "cat") into a goal word (e.g., "dog") by changing one letter at a time, ensuring all intermediate transformations are valid words.
The predefined dictionary ensures that only valid words are used at each step.
Algorithms Implemented: BFS, DFS, A*, and Bidirectional Search.
Search Algorithms Implemented:
Breadth-First Search (BFS)

Explores nodes level by level, ensuring the shortest path to the goal but may require a lot of memory.
Depth-First Search (DFS)

Explores as far as possible along one branch before backtracking. It may be inefficient for deeper states, especially in large state spaces like 8-puzzle.
Warning: DFS might take a long time to find solutions, particularly in complex puzzles.
A Search*

Uses a heuristic function to guide the search, making it more efficient than BFS or DFS.
Heuristic Example: Manhattan distance is used in the 8-puzzle to estimate the distance to the goal.
Bidirectional Search

Runs two searches simultaneously from the start and goal states, meeting in the middle. This often improves efficiency compared to traditional single-direction searches.
User Interaction and Features:
Randomize Functionality: Each game provides a randomization feature to generate different problem instances.
Visualization of Search Process: Smooth animations display the state changes during the search process.
Performance Metrics Display: Each run shows the time taken and nodes expanded, allowing for a comparative study of algorithms.
Interactive GUI: The GUI, built using Tkinter, provides easy-to-use buttons to switch between games, trigger solutions, and choose algorithms.
Algorithm Comparison: The project allows users to explore the trade-offs between algorithms and understand which one performs best in different contexts.
Objective and Learning Outcome:
The main objective of this project is to provide hands-on experience with various search algorithms by applying them to real-world-like problem spaces. The interactive visualization and performance metrics empower users to understand the strengths and limitations of each algorithm in different search scenarios. Users will learn how state-space search works, how heuristics guide A* search, and how algorithms behave differently across maze solving, string transformations, and sliding tile puzzles.
"# INFO_550_AI_PROJECT" 
<<<<<<< HEAD
"# INFO_550_AI_PROJECT" 
=======
>>>>>>> 1b30d0532331cdf25164c0fb9b52c825e8e0f404
