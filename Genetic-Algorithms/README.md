# Genetic Algorithms

This folder contains a Python implementation of a **Genetic Algorithm (GA)** designed to maximize a simple mathematical function.

---

## Project: Maximize x² using GA

### Description
The goal of this project is to use a Genetic Algorithm to find the value of `x` (between 0 and 31) that **maximizes** the function:

f(x) = x^2


The GA includes the following steps:
1. **Population Initialization** – Generate a random population of binary-encoded chromosomes.
2. **Fitness Evaluation** – Evaluate each chromosome based on the function `x^2`.
3. **Selection** – Select the top-performing chromosomes for reproduction.
4. **Crossover** – Combine pairs of chromosomes to generate new children.
5. **Mutation** – Randomly flip bits in a chromosome to maintain genetic diversity.
6. **Iteration** – Repeat the process for a set number of generations or until the target solution is found.

---

### Files
- `GA_maximize_function1.py` : The main Python file containing the GA implementation.

---

### How to Run
1. Clone this repository or download the folder.
2. Navigate to the folder in your terminal.
3. Run the script using Python:

```bash
python GA_maximize_function1.py

Notes

The chromosome is 5-bit binary representing integers from 0 to 31.

The algorithm stops when it finds the maximum value (x = 31) or after a set number of generations.

Randomness in selection, crossover, and mutation means results may vary slightly between runs.
