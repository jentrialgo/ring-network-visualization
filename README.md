# Ring Network Visualization

A minimalistic, interactive tool to visualize ring networks with configurable parameters.
Built with vanilla JavaScript and HTML5 Canvas, this project demonstrates network topology
with a focus on simplicity and elegance.

## Features
- Visualize a ring network with `N` nodes.
- Set each node's degree (`n`) and step size (`s`) for additional connections.
- Two interactive modes:
  - **Neighbors**: Highlights a node and its direct connections.
  - **Distances**: Shows shortest path distances from a selected node.
- Displays network metrics: diameter and average diameter.

## Usage
1. Open the visualization in your browser (e.g., via GitHub Pages).
2. Configure the parameters:
   - **`N`**: Number of nodes (minimum 3).
   - **`n`**: Degree of each node (minimum 2, includes ring connections).
   - **`s`**: Step size for extra connections (minimum 1, only applies if `n > 2`).
   - **Mode**: Choose "Neighbors" or "Distances" from the dropdown.
3. Interact by hovering over nodes to see highlights and labels.

## Demo
Try it live at
[https://jentrialgo.github.io/ring-network-visualization/](https://jentrialgo.github.io/ring-network-visualization/).

## Installation
No installation required! Simply:
1. Clone or download this repository.
2. Open `index.html` in a web browser.

```bash
git clone https://github.com/yourusername/ring-network-visualization.git
cd ring-network-visualization
open index.html