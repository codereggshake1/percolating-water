# Water Percolation
An NxN grid have cells that can start out either opened or closed, with probability $p$ to be opened. Water starts at the top and spreads out to open cells and fills those cells up. When the water can no longer reach any open cells, the process terminates. 

**Question 1**: Given $p$, the probability of a cell being opened, what is the probability that the grid percolates? A grid percolates if there's a path from the top to the bottom.

**Question 2**: Given $p$, how many "frontier cells" are there? A frontier cell is a closed cell that is adjacent to a water cell.

# Features
- 🪜 Step through the percolation process
- 🎲 Simulate range of values of $p$
- 👀 Visualize how changing $p$ changes percolation probability and frontier cell counts

# Run
1. Install [NiceGUI](https://nicegui.io/).
2. Run `python main.py`

# Implementation
- NiceGui
- grid util (really slow)

# Sources
- https://introcs.cs.princeton.edu/java/24percolation/

