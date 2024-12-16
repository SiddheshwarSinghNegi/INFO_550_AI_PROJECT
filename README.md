AI Search Problem Solver

Introduction

The AI Search Problem Solver is a comprehensive project that explores three distinct problem domains: maze solving, string transformation, and the 8-puzzle problem. It implements and compares various search algorithms, including Depth-First Search (DFS), Breadth-First Search (BFS), Uniform Cost Search (UCS), A* (with Manhattan and Euclidean heuristics), and Bidirectional Search. The project evaluates these algorithms' performance in terms of execution time, memory usage, and the number of nodes expanded, offering insights into their efficiency and applicability to different problem types.
________________________________________

Features

•	Algorithms Implemented:

    o	Depth-First Search (DFS)
    
    o	Breadth-First Search (BFS)
    
    o	Uniform Cost Search (UCS)
    
    o	A* (Manhattan Heuristic & Euclidean Heuristic)
    
    o	Bidirectional Search

•	Problems Solved:

1.	Maze Solving Problem: Navigate from the top-left to the bottom-right corner of a maze.
2.	String Transformation Problem: Transform one word into another by changing one letter at a time.
3.	8-Puzzle Problem: Arrange tiles in a 3x3 grid to match a specified goal state.

•	Visualization:

    o	Step-by-step animations for each algorithm’s search process.
    
    o	Detailed GUI built with Tkinter for easy interaction.
________________________________________

Heuristics Used in A*

•	Manhattan Heuristic:

    o	Sum of absolute differences between the current and goal positions.
    
    o	Best suited for grid-based problems like mazes and sliding puzzles.

•	Euclidean Heuristic:

    o	Straight-line distance to the goal.
    
    o	Suitable for problems where diagonal movements are allowed.
________________________________________

Key Findings

1.	A* (with Manhattan Heuristic) consistently outperformed other algorithms in terms of efficiency and memory usage.
2.	Bidirectional Search reduced search depth, especially in symmetrical problems like maze solving, but struggled with complex branching in the 8-puzzle problem.
3.	UCS explored significantly more nodes compared to heuristic-driven algorithms like A*, highlighting the importance of domain-specific heuristics.
________________________________________

Setup Instructions

1.	Clone the Repository:
   
git clone https://github.com/SiddheshwarSinghNegi/INFO_550_AI_PROJECT.git

cd INFO_550_AI_PROJECT

3.	Dependencies:
   
    o	Python 3.x
    
    o	Jupyter Notebook
    
    o	NumPy
    
    o	Tkinter (Pre-installed with Python)

5.	Run the Project:
   
    o	Open the desired .ipynb file (e.g., Maze Solver.ipynb, Puzzle App.ipynb, or String Transformer.ipynb) in Jupyter Notebook or JupyterLab.
    o	Run the notebook cells to execute the selected game and algorithm.
________________________________________

Future Enhancements

1.	Extend the 8-Puzzle to larger configurations (e.g., 15-Puzzle) for scalability testing.
2.	Develop advanced heuristics for the String Transformation Problem.
3.	Conduct scalability analyses under varying problem complexities.
________________________________________

Repository Contents

•	Maze Solver.ipynb: Implementation of the Maze Solving Problem.

•	Puzzle App.ipynb: Implementation of the 8-Puzzle Problem.

•	String Transformer.ipynb: Implementation of the String Transformation Problem.

•	README.md: Project documentation.
________________________________________

Author

Siddheshwar Singh Negi

Master’s Student, College of Information Science, University of Arizona

