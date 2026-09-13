# Traveling Salesperson Problem (TSP) — Genetic Algorithm
A Python-based implementation of a Genetic Algorithm (GA) to solve the 2D Traveling Salesperson Problem (TSP) by finding a near-optimal closed tour through 30 cities on a coordinate grid.

Key Features:
* Permutation Encoding: Direct city sequence representation.
* Tournament Selection: Evaluates route fitness based on Euclidean distance minimization.
* Ordered Crossover (OX): Preserves relative city order without introducing duplicates.
* Inversion Mutation: Reverses a random tour segment to escape local optima.
* Elitism: Retains top-performing individuals across generations.
* Live Animation: Dynamic generation-by-generation route plotting using matplotlib and IPython.display.  
