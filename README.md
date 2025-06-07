# N-Queen-GA 🏰♟️

![N-Queen-GA](https://img.shields.io/badge/N--Queen--GA-Active-brightgreen)

Welcome to the N-Queen-GA repository! This project focuses on solving the N-Queen problem using a Genetic Algorithm implemented in both C and Python3. We utilize PMX (Partially Matched Crossover) to enhance the evolutionary process, making our approach both efficient and effective.

## Table of Contents

- [Introduction](#introduction)
- [What is the N-Queen Problem?](#what-is-the-n-queen-problem)
- [Genetic Algorithm Overview](#genetic-algorithm-overview)
- [PMX Crossover](#pmx-crossover)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The N-Queen problem is a classic challenge in computer science and artificial intelligence. The goal is to place N queens on an N×N chessboard so that no two queens threaten each other. This means no two queens can share the same row, column, or diagonal. Our repository provides a robust solution using a Genetic Algorithm, which is a powerful method for optimization problems.

You can find the latest releases of this project [here](https://github.com/Aryan7441/N-Queen-GA/releases). Download the necessary files and execute them to see the algorithm in action!

## What is the N-Queen Problem?

The N-Queen problem is a well-known puzzle that involves placing N queens on a chessboard of size N×N. The challenge lies in ensuring that no two queens can attack each other. This problem has been extensively studied in the fields of computer science, mathematics, and artificial intelligence.

### Problem Statement

Given an integer N, your task is to find all possible arrangements of N queens on an N×N chessboard. Each arrangement must satisfy the constraint that no two queens can threaten each other.

### Example

For N = 4, one possible solution is:

```
. Q . .
. . . Q
Q . . .
. . Q .
```

In this arrangement:
- Q represents a queen.
- . represents an empty space.

## Genetic Algorithm Overview

A Genetic Algorithm (GA) is a search heuristic inspired by the process of natural selection. It is used to find approximate solutions to optimization and search problems. The key components of a GA include:

1. **Population**: A set of potential solutions.
2. **Selection**: Choosing the best solutions from the population.
3. **Crossover**: Combining two parent solutions to create offspring.
4. **Mutation**: Introducing random changes to solutions to maintain diversity.

The GA iteratively improves the population by applying these operations until a satisfactory solution is found.

## PMX Crossover

PMX (Partially Matched Crossover) is a crossover technique used in genetic algorithms. It helps maintain the relative order of genes from the parent solutions while producing offspring. This is particularly useful in problems like the N-Queen, where the arrangement of queens matters.

### How PMX Works

1. Select two parent solutions.
2. Choose two crossover points.
3. Copy the segment between the crossover points from one parent to the offspring.
4. Fill the remaining positions using the other parent while maintaining the order of elements.

This method helps retain useful traits from both parents, leading to better solutions over generations.

## Project Structure

The repository is organized as follows:

```
N-Queen-GA/
├── C/
│   ├── main.c
│   ├── ga.c
│   ├── ga.h
│   └── Makefile
├── Python3/
│   ├── main.py
│   ├── ga.py
│   └── requirements.txt
└── README.md
```

- **C/**: Contains the C implementation of the Genetic Algorithm.
- **Python3/**: Contains the Python implementation of the Genetic Algorithm.
- **README.md**: This file.

## Getting Started

To get started with the N-Queen-GA project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Aryan7441/N-Queen-GA.git
   cd N-Queen-GA
   ```

2. **Choose your implementation**:
   - For C, navigate to the `C` directory.
   - For Python3, navigate to the `Python3` directory.

3. **Build the C implementation**:
   ```bash
   cd C
   make
   ```

4. **Install Python dependencies** (for Python3):
   ```bash
   cd Python3
   pip install -r requirements.txt
   ```

## Usage

### C Implementation

To run the C implementation, execute the following command in the `C` directory:

```bash
./ga <N>
```

Replace `<N>` with the number of queens you wish to solve for.

### Python3 Implementation

To run the Python3 implementation, execute the following command in the `Python3` directory:

```bash
python main.py <N>
```

Again, replace `<N>` with the number of queens.

You can find the latest releases of this project [here](https://github.com/Aryan7441/N-Queen-GA/releases). Download the necessary files and execute them to see the algorithm in action!

## Contributing

We welcome contributions to the N-Queen-GA project. If you wish to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please reach out to the project maintainer:

- **Name**: Aryan
- **Email**: aryan@example.com

Thank you for checking out the N-Queen-GA project! We hope you find it useful in your studies and projects related to algorithms and optimization.