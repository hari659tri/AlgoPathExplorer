# AlgoPath Explorer is an interactive React web app that visually demonstrates and compares four key pathfinding algorithms: BFS, DFS, Dijkstra's, and A*. Users can create custom grids with walls and watch as the algorithms find a path in real time.

## 🚀 About the Project

Welcome to **AlgoPath Explorer**! This project is an interactive web application built with **React** that visually demonstrates the behavior of four popular pathfinding algorithms: Breadth-First Search (**BFS**), Depth-First Search (**DFS**), **Dijkstra's Algorithm**, and **A\* Search**.

The application allows users to:
* Visualize how each algorithm finds the shortest (or a valid) path from a start node (green) to an end node (red) on a grid.
* Add walls to the grid by clicking and dragging, creating obstacles for the algorithms to navigate around.
* Compare the performance and characteristics of different algorithms side-by-side.

This tool is perfect for students, developers, or anyone interested in understanding how these fundamental computer science algorithms work in a real-time, visual environment.

## 🌟 Features

* **Interactive Grid:** Create your own custom mazes and scenarios.
* **Algorithm Showcase:** Visualize the step-by-step process of BFS, DFS, Dijkstra's, and A\* Search.
* **Guaranteed Shortest Path:** Witness algorithms like BFS and Dijkstra's guarantee the shortest path, and see why DFS does not.
* **Real-time Animations:** Watch the algorithms animate their search, highlighting explored nodes and the final path.

## 🧠 Understanding the Algorithms

### **Breadth-First Search (BFS)**
BFS explores a graph level by level, or in a radial pattern, from the starting node. It finds the shortest path in terms of the number of steps (unweighted paths) because it always explores all neighbors at the current "depth" before moving on to the next level of neighbors.

### **Depth-First Search (DFS)**
DFS explores as far as possible along a single path before it "backtracks" and tries another route. Think of it like navigating a maze by always sticking to the right wall. This approach does not guarantee finding the shortest path, as it might go down a very long, valid path before finding a shorter one.

### **Dijkstra's Algorithm**
Dijkstra's algorithm is designed to find the shortest path from a starting node to all other nodes in a weighted graph. Unlike BFS, it prioritizes paths with a lower "cost" (weight), making it ideal for scenarios where different paths have different travel times or distances.

### **A\* Search**
A\* is a more advanced version of Dijkstra's, optimized for finding the shortest path to a *single* destination. It uses a "heuristic" (a smart guess) to estimate the distance to the goal, allowing it to more intelligently prioritize which paths to explore. This makes it significantly more efficient and is considered the industry standard for pathfinding in games and navigation systems.

## 🏃 Getting Started

To run this project locally, follow these steps.

### Prerequisites

You need to have **Node.js** installed on your machine. You can download it from [nodejs.org](https://nodejs.org/). Node.js comes bundled with npm and npx.

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd your-repository-name
    ```
3.  Install the dependencies:
    ```bash
    npm install
    ```

### Running the App

Start the application in development mode:
```bash
npm start
```
This will open the app in your default web browser at `http://localhost:3000`. The page will automatically reload as you make changes to the code.

## 🏗️ Project Structure

The core logic of the application resides in the `src/PathfindingVisualizer/` directory.

* `PathfindingVisualizer.jsx`: The main React component that handles the grid, user interactions (mouse events), and visualization logic.
* `algorithms/`: A folder containing the implementations of each pathfinding algorithm (e.g., `dijkstra.js`, `bfs.js`, etc.).
* `PathfindingVisualizer.css`: Styling for the components, including the grid, nodes, and walls.

## 📦 Deployment

This project is deployed using **GitHub Pages**.

### Building for Production

To build the app for a production environment, run:
```bash
npm run build
```
This command creates an optimized `build` folder ready for deployment.

---

## 🤝 Contributing

This project is open for contributions! If you have suggestions for new features, bug fixes, or improvements, feel free to open an issue or create a pull request.


