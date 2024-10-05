# N-Queens Visualiser

**N-Queens Visualiser** is an interactive web application designed to visually demonstrate the N-Queens problem using backtracking algorithm. The application allows users to  view each step as the algorithm progresses, and better understand how backtracking  solve the problem.

## Demo
 **Deployed link**: [N-Queens-Visualiser](https://n-queens-visualiser-by-akarsh.netlify.app/)
## Features
- **Visual Representation**: See real-time visualization of the algorithm placing queens on the chessboard.
- **Backtracking Algorithms**: Explore solutions using **Backtracking** algorithm.
- **Dynamic Board Size**: Users can select any board size (N x N) from 1 to 10.
- **Step-by-Step Execution**: Watch the algorithm's decision-making process step-by-step.
- **Solution Count**: Shows the number of distinct solutions found for a given board size.
- **User Controls**: Play, pause, and adjust the speed of visualization.

## Technologies Used
- **HTML/CSS**: For structuring and styling the visualizer.
- **JavaScript**: For implementing the logic behind various algorithms.
- **Bootstrap**: For responsive UI components.
  
## Project Structure
- **index.html**: Contains the main structure of the web page.
- **styles.css**: Styling for the chessboard and user controls.
- **script.js**: Core logic and algorithms for the N-Queens problem.


## How It Works
The **N-Queens problem** involves placing N queens on an N x N chessboard such that no two queens can attack each other. The application solves the problem using backtracking  algorithm and provides a step-by-step visualization of the queens being placed, conflicting positions, and backtracking.

### Key Algorithms Implemented:
1. **Backtracking**: Places queens one by one and backtracks if conflicts arise.
3. **Brute Force** (Optional): Places queens in all possible ways and checks constraints.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Akarsh2012/N-Queens-Visualiser.git
   ```
2. Open the project folder:
   ```bash
   cd N-Queens-Visualiser
   ```
3. Open index.html in your browser to start the visualizer.

## Usage
- Select the board size (N) using the dropdown menu.
- Use the Play and Pause buttons to control the visualization.
- Adjust the speed slider to change the speed of the visualization.

  
## Future Improvements
- More Algorithms: Implement additional algorithms such as Simulated Annealing or Genetic Algorithm for solving the N-Queens problem.
- Algorithm Comparison: Add a feature to run multiple algorithms side-by-side to compare their performance.
- Dark Mode: Provide a dark mode option to enhance the user experience during long sessions.

## Contributing
- Contributions are welcome! If you have suggestions or want to add new features, please fork the repository and submit a pull request.
