# Routing Simulation

This repository contains the `routing_sim.cpp` file, which simulates network routing algorithms.

## Features

- Simulates routing protocols using different algorithms:
    - **Distance Vector Routing (DVR)**: Implements the Floyd-Warshall algorithm
    - **Link State Routing (LSR)**: Implements Dijkstra's algorithm.

## File Overview

- **`routing_sim.cpp`**: The main source code for the routing simulation, including implementations of DVR and LSR algorithms.

## Prerequisites

- C++ compiler (e.g., `g++`).
- Standard C++ libraries.

## How to Run

1. **Compile the Code**  
        Use the following command to compile the program:  
        ```
        g++ -o routing_sim routing_sim.cpp
        ```

2. **Run the Program**  
        Execute the compiled program:  
        ```
        ./routing_sim input1.txt
        ```

## Example

```bash
g++ -o routing_sim routing_sim.cpp
./routing_sim input1.txt
```

## Contributors

- Abhishek Khandelwal 220040
- Pallav Goyal 220747
- Poojal Katiyar 220770
