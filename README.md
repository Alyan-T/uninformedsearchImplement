Authors: M. Alyan Tariq & Sanial 

This project is an AI Pathfinder developed to visualize how various uninformed search algorithms navigate a grid environment to find a target while avoiding both static and dynamic obstacles. The GUI visualizes the step-by-step frontier expansion, explored nodes, and the final path.

The following fundamental search strategies are included:
* Breadth-First Search (BFS)
* Depth-First Search (DFS)
* Uniform-Cost Search (UCS)
* Depth-Limited Search (DLS)
* Iterative Deepening DFS (IDDFS)
* Bidirectional Search

Node expansion strictly follows an 8-way clockwise order, starting from the 'Up' direction.

The environment features a dynamic hurdle system. During the agent's movement phase, there is a 5% probability per step that a new obstacle will spawn on an empty node. If the obstacle blocks the calculated path, the agent will handle the runtime exception and automatically re-plan a new route to the target.
This project was built to run inside a Jupyter Notebook environment using Matplotlib for inline visualization.
1. Ensure you have Python installed.
2. Install the required dependencies by running the following command in your terminal:
   pip install matplotlib numpy ipython
