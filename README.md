# Parallelization of K-Means Clustering Algorithm

## Overview
This project demonstrates the parallelization of the K-Means clustering algorithm using a **Master-Slave (MapReduce)** architecture. [cite_start]The goal is to optimize the computationally intensive task of cluster assignment by distributing data chunks across multiple CPU cores, significantly reducing total execution time for large-scale datasets[cite: 1].

## Assignment Structure
The project follows the specific requirements for ML System OPS Assignment 02:
* [cite_start]**[P0] Problem Formulation**: Analysis of Amdahl's Law and communication costs[cite: 1].
* [cite_start]**[P1] Design**: Proposed Master-Slave architecture for workload distribution[cite: 1].
* [cite_start]**[P1 Revised] Implementation Details**: Adaptation for macOS/Jupyter environments using the `multiprocess` library[cite: 1].
* [cite_start]**[P2] Implementation**: Complete Python implementation in a Jupyter Notebook[cite: 1].
* [cite_start]**[P3] Testing & Results**: Performance evaluation comparing serial vs. parallel execution times.

## System Requirements
To run this notebook, ensure you have the following installed:
* [cite_start]Python 3.8+ (Tested on 3.13.5) 
* Jupyter Notebook or Jupyter Lab
* Libraries: `numpy`, `scikit-learn`, `multiprocess`

> [cite_start]**Note:** We use the `multiprocess` library instead of the standard `multiprocessing` to ensure compatibility with macOS `spawn` methods and Jupyter's interactive shell.

## Installation
```bash
pip install numpy scikit-learn multiprocess
