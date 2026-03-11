# 🧩 Python 8-Puzzle Solver – Search Algorithms & Heuristics

## 📌 Project Overview

The **8-Puzzle Solver** is a Python-based project that implements **classic search algorithms and heuristic techniques** to solve the 8-puzzle problem. The 8-puzzle consists of a 3x3 grid containing 8 numbered tiles and one empty space. The objective is to slide the tiles to reach a goal configuration.

This project explores three major search algorithms:

- **Breadth-First Search (BFS)**
- **Depth-First Search (DFS)**
- **A* Search Algorithm** with two heuristics:
  - **Manhattan Distance**
  - **Euclidean Distance**

The solver allows users to input any initial puzzle configuration, choose a solving algorithm, and view the solution path. It also checks for puzzle solvability using **inversion counting**.

---

## 🎯 Key Features

- **Algorithm Flexibility:** Users can select BFS, DFS, or A* algorithms.
- **Heuristic Options:** A* Search leverages Manhattan and Euclidean distances for optimal solutions.
- **Solution Path Display:** Outputs the sequence of moves to solve the puzzle.
- **Solvability Check:** Automatically validates whether a puzzle configuration is solvable.
- **Modular Design:** Easy to extend with new algorithms or heuristics.

---

## 🧰 Tools and Technologies Used

| Tool / Library      | Purpose                                                   |
| ------------------ | --------------------------------------------------------- |
| Python              | Core programming language for algorithm implementation   |
| Tkinter             | GUI library for interactive puzzle interface             |
| psutil              | Monitor memory usage during algorithm execution          |
| Queue / PriorityQueue | Data structures for BFS, DFS, and A* algorithms        |

---

## 💻 Software Requirements

- Python 3.8 or higher
- Tkinter (for GUI)
- psutil library (`pip install psutil`)

---

## 🖥 Hardware Requirements

- Processor capable of handling computational tasks
- Minimum 4GB RAM (8GB recommended for larger puzzles)

---

## 🧩 How It Works

1. **Input Puzzle Configuration:** Users enter the initial state of the 8-puzzle.
2. **Select Algorithm:** Choose BFS, DFS, or A* Search.
3. **Check Solvability:** The program verifies if the puzzle can be solved.
4. **Compute Solution Path:** Algorithm finds the sequence of moves.
5. **Display Results:** Outputs the moves and optionally shows the puzzle solution in GUI.

---

## 🔑 Key Concepts Explored

- **Breadth-First Search (BFS):** Explores all nodes level by level to guarantee shortest path solutions.
- **Depth-First Search (DFS):** Explores nodes deeply before backtracking; may not always find shortest path.
- **A* Search Algorithm:** Combines cost-so-far and heuristic estimate to find efficient solutions.
- **Heuristics:**
  - **Manhattan Distance:** Sum of the vertical and horizontal distances of tiles from their goal positions.
  - **Euclidean Distance:** Straight-line distance of tiles from their goal positions.

---

## 📊 Architecture

The system is designed modularly to facilitate:

- **Algorithm Integration:** Easily add new search strategies.
- **Heuristic Flexibility:** Introduce additional heuristics.
- **User Interaction:** Console-based or GUI interfaces.
- **Memory Management:** Optimized using Python data structures and psutil.

---

## 🏁 Conclusion

The 8-Puzzle Solver project demonstrates **practical implementation of search algorithms and heuristics** for solving a classical AI problem. Key accomplishments include:

- Successful implementation of **BFS, DFS, and A* Search** algorithms.
- Integration of **heuristic functions** for intelligent search strategies.
- Modular and extensible design for future enhancements.

---

## 🌟 Future Scope

Potential improvements and extensions:

1. **Advanced Algorithms:** Integrate IDA*, Greedy Search, or other informed strategies.
2. **Additional Heuristics:** Explore novel heuristics beyond Manhattan and Euclidean distances.
3. **Graphical User Interface:** Transition to a fully interactive GUI showing puzzle moves visually.
4. **Parallel Processing:** Optimize execution time using multithreading or multiprocessing.
5. **Enhanced User Features:** Include real-time progress updates, pause/resume options, and step-by-step walkthrough.

---

## 👨‍💻 Author

**Thanniru Dharma Nithin**  
Data Analytics & Python Enthusiast – Coding Ninjas  
GitHub: [https://github.com/ThanniruDharmaNithin](https://github.com/ThanniruDharmaNithin)  

---

⭐ If you find this project useful, feel free to star the repository!
