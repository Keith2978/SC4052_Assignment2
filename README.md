# Ranking Algorithm Stability Testing

## Overview

This project provides implementations of four ranking algorithms used to measure the **stability** of node rankings in directed graphs:
- **PageRank**
- **HITS**
- **Randomized HITS**
- **Subspace HITS**

The stability of each algorithm is evaluated by perturbing the graph (removing edges) and measuring how much the node rankings change using the **L1 norm**. This helps assess how robust each algorithm is to structural changes in the graph.

## Features

- **PageRank**: Measures the importance of a node based on its connections and the importance of the connected nodes.
- **HITS**: Computes hub and authority scores for nodes in the graph.
- **Randomized HITS**: A randomized variant of the HITS algorithm.
- **Subspace HITS**: Uses eigenvalue decomposition to compute hub and authority scores based on the most important eigenvectors.
