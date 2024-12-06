INFO_550_AI_Search_Games_Project

This project explores AI search algorithms—BFS, DFS, A*, Bidirectional Search, and UCS—across three games: Maze Solver, 8-Puzzle, and String Transformation. Each game offers unique challenges in state-space search, enabling a comparative analysis of these algorithms' efficiency and effectiveness in terms of time and space complexity. An interactive graphical user interface (GUI) with smooth animations visualizes the behavior of the search algorithms, making it intuitive and educational for users.
Key Features

1.	Heuristic Design

The project incorporates multiple heuristics for each problem to analyze their impact:

o	Maze Solver: Manhattan distance and Euclidean distance.

o	8-Puzzle: Manhattan distance, misplaced tiles, and linear conflict.

o	String Transformation: Hamming distance and advanced word similarity heuristics.

2.	Algorithm Comparisons

The project includes UCS for baseline comparisons with A* and Bidirectional A*, showcasing the importance of heuristics in improving search efficiency and optimality.

3.	Predictions and Testing

Predictions are made about the effectiveness of heuristics under varying conditions. For instance:

o	A* with Manhattan distance is expected to perform best in Maze and 8-Puzzle.

o	Bidirectional Search excels in symmetrical problems like String Transformation.


4.	Interactive GUI

o	Randomization: Generates diverse problem configurations for each game.

o	Smooth Animations: Visualizes node exploration and path reconstruction during the search process.

o	Performance Metrics: Displays time taken, nodes expanded, and solution paths for each algorithm.

Games Implemented

1. Maze Solver
•	Randomly generated mazes with walls, start (green), and goal (red) points.
•	Algorithms: BFS, DFS, A*, Bidirectional Search, and UCS.
•	Heuristics: Manhattan distance, Euclidean distance.

2. 8-Puzzle
•	Sliding tile puzzle with randomized solvable configurations.
•	Algorithms: BFS, DFS, A*, Bidirectional Search, and UCS.
•	Heuristics: Manhattan distance, misplaced tiles, linear conflict.
•	Warning: DFS may take significantly longer for complex configurations.

3. String Transformation
•	Transform a start word into a goal word by changing one letter at a time, ensuring all intermediate transformations are valid words.
•	Algorithms: BFS, DFS, A*, Bidirectional Search, and UCS.
•	Heuristics: Hamming distance, advanced word similarity measures.

Search Algorithms

Breadth-First Search (BFS)
•	Explores nodes level by level, ensuring the shortest path to the goal.
•	Memory-intensive but guarantees optimality.

Depth-First Search (DFS)
•	Explores as far as possible along one branch before backtracking.
•	May be inefficient for deeper states and large state spaces.

A* Search
•	Combines path cost and heuristic to guide the search.
•	Efficient and guarantees optimality with admissible heuristics.

Bidirectional Search
•	Runs two searches simultaneously from the start and goal states, meeting in the middle.
•	Reduces the search space significantly in many scenarios.

Uniform Cost Search (UCS)
•	Similar to A* but does not include heuristics.
•	Serves as a baseline to evaluate the impact of heuristics.

Learning Outcomes
•	Understand state-space search through interactive visualizations.
•	Analyze the trade-offs between algorithms and their performance in different problem domains.
•	Explore the role of heuristics in improving search strategies.
•	Evaluate the strengths and weaknesses of Bidirectional Search in both spatial and non-spatial problems.
