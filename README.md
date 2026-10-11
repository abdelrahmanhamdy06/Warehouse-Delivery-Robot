# Warehouse Delivery Robot - Search Algorithms

This repository contains the solution for **Task 1: Search Algorithms** for the Intelligent Systems course at the **Faculty of Computers and Data Science, Alexandria University**.

## Project Overview
The project simulates a warehouse delivery robot that needs to find the optimal path from a starting position (`S`) to a goal position (`G`) on a grid map. The robot can move Up, Down, Left, or Right. The grid consists of different terrains with varying movement costs.

**Map Legend & Costs:**
*   `S` : Start cell (Cost: 0)
*   `G` : Goal cell (Cost of entering: 1)
*   `.` : Normal floor (Cost: 1)
*   `~` : Rough floor (Cost: 3)
*   `#` : Wall (Impassable)

## Algorithms Implemented
To ensure the robot finds the optimal path, we implemented two search algorithms in Python without using external path-finding libraries:

1.  **Uniform Cost Search (UCS):** An uninformed search algorithm that expands nodes based on the lowest cumulative path cost g(n).
2.  **A* Search (A-Star):** An informed search algorithm that uses the Manhattan Distance as an admissible heuristic h(n). It optimizes the search process by expanding nodes based on f(n) = g(n) + h(n).

## How to Run the Code
1. Ensure you have a Jupyter Notebook environment (like JupyterLab or Anaconda) or use Google Colab.
2. Open the `Intelligent_Programming.ipynb` file.
3. The maps (`MAP_A`, `MAP_B`, `MAP_C`) are predefined as variables at the top of the notebook.
4. Run all the cells sequentially from top to bottom.
5. The final outputs will display the paths on the grids, print the total cost, show the number of expanded nodes, and generate a performance comparison table between UCS and A*.

## Team Members
*   [Name of Student 1] - ID: [Insert ID 1]
*   [Name of Student 2] - ID: [Insert ID 2]
*   [Name of Student 3] - ID: [Insert ID 3]
