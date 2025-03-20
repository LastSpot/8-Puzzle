# 8-Puzzle Solver

## Description

This project implements a solver for the classic 8-puzzle problem, a sliding puzzle that consists of a 3x3 grid with 8 numbered tiles and one empty space. The goal is to rearrange the tiles from a given initial state to reach the goal state by sliding tiles into the empty space.

Example of a goal state:
```
1 2 3
4 5 6
7 8 _
```
Where '_' represents the empty space.

## Features

- Solves 8-puzzle problems using search algorithms
- Visualizes the puzzle state and solution path
- Provides step-by-step solution guidance
- Includes multiple solving algorithms for comparison

## Installation

### Prerequisites

- Python 3.7 or higher
- Required Python packages (install using pip):
```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
```bash
git clone [repository-url]
cd 8-Puzzle
```

2. Run the solver:
```bash
python solver.py
```

## Algorithms

The solver implements the following algorithms:

- A* Search (with Manhattan Distance heuristic)
- Breadth-First Search (BFS)
- Depth-First Search (DFS)

## Project Structure

```
8-Puzzle/
├── solver.py     # Main solver implementation
├── puzz.py       # Puzzle state and mechanics
├── pdqpq.py     # Priority queue implementation
└── README.md
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to all contributors who have helped with the development
- Special thanks to the computer science community for the algorithms and concepts used in this project

## Contact

For any questions or feedback, please open an issue in the repository. 