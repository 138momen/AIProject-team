# AIProject-team
AI project for university using search algorithms
still working on it so expect unfinished parts
# 8-Puzzle Solver: AI Search Algorithms

## 📌 Project Overview
This project implements a comprehensive framework for solving the classic **8-Puzzle** game using various Artificial Intelligence search strategies.

[cite_start]The primary objective is to analyze and compare the performance of different search algorithms in terms of **time complexity**, **space complexity**, and **solution optimality**[cite: 4, 10]. This project serves as a practical application of fundamental AI concepts as part of the Introduction to Artificial Intelligence course.

## 🧩 The Problem: 8-Puzzle
The 8-puzzle is a sliding puzzle that consists of a 3x3 frame of numbered square tiles (1-8) in random order with one tile missing. [cite_start]The object of the puzzle is to place the tiles in order by making sliding moves that use the empty space[cite: 18].

## 🚀 Features & Algorithms
[cite_start]This framework implements the following search strategies as required by the project proposal[cite: 23, 24, 26]:

### Uninformed Search Strategies
1.  [cite_start]**Breadth-First Search (BFS):** Explores the neighbor nodes first, before moving to the next level neighbors[cite: 25].
2.  [cite_start]**Depth-First Search (DFS):** Explores as far as possible along each branch before backtracking[cite: 25].
3.  [cite_start]**Iterative Deepening Search (IDS):** A state space search strategy in which a depth-limited search is run repeatedly, increasing the depth limit with each iteration[cite: 28].

### Informed Search Strategies
4.  [cite_start]**Uniform-Cost Search (UCS):** Expands the least-cost unexpanded node[cite: 27].
5.  **A* Search (A-Star):** Uses a heuristic function to guide the search.
    * [cite_start]**Heuristic Used:** Manhattan Distance (Sum of the vertical and horizontal distances of the tiles from their goal positions)[cite: 29].
6.  **Hill Climbing:** A local search algorithm that continuously moves in the direction of increasing value/decreasing cost.

## 📂 Project Structure
The repository is organized as follows:


└── README.md             # Project documentation
