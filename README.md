# Connect 4 AI Agents and Game Simulator

This repository contains a set of AI agents and a game simulator for playing the classic Connect 4 game. The project includes implementations of various AI strategies, a game environment, and a script for running multiple games to evaluate AI performance.

## Project Overview

### Description

The goal of this project is to implement and evaluate different AI agents for the Connect 4 game. The project includes a game environment and multiple AI agents, each with a unique strategy for playing the game. The key components of this project include:

1. **Game Environment**: A Connect 4 game environment that supports multiple players and visualizations.
2. **AI Agents**: Various AI agents with different strategies, including human players, random moves, minimax algorithm, alpha-beta pruning, and Monte Carlo simulations.
3. **Simulation and Evaluation**: Scripts to run and evaluate the performance of these AI agents in a series of games.

### Significance

The project is significant for several reasons:

1. **AI Strategy Comparison**: It allows for the comparison of different AI strategies in a controlled environment.
2. **Reinforcement Learning**: Provides insights into reinforcement learning techniques and their application in game playing.
3. **Educational Value**: Serves as a practical example of implementing AI algorithms and game simulations.

## File Structure

- `PA3.ipynb`: The main Jupyter notebook containing the assignment instructions, code cells, and markdown documentation.
- `connect4.py`: Contains the game environment for Connect 4, including game logic and visualization.
- `players.py`: Defines the various AI agents and human players.
- `montecarlo.py`: Implements the Monte Carlo AI agent.
- `thread.py`: Contains utility classes for managing threads.
- `main.py`: The main script to set up and run Connect 4 games between different agents.
- `run.sh`: A script to automate running multiple games and collecting results.

## Setup Instructions

1. **Run a GPU Instance**:
   - Go to `Runtime` -> `Change runtime type` -> `Hardware accelerator` -> Select `GPU`.
   - Ensure that "using CUDA" prints in the training script.

2. **Prerequisites**:
   - Before writing any code, make sure you can run up to and including the `DQN.py` cell.
   - The `Test` cell should error out with a message about not implementing action (implementing this part is part of your assignment).

3. **Handling Prompts**:
   - When you reach the line:
     ```
     [Y]es, [N]o, [A]ll, n[E]ver, [R]ename, [Q]uit
     ```
     - Press the stop button on the cell, and it will continue running.

## How to Run

1. Open the `PA3.ipynb` notebook in Jupyter.
2. Follow the instructions provided in the markdown cells.
3. Run each cell sequentially to ensure that dependencies are loaded correctly.
4. Implement the required parts as indicated in the assignment.

## Notes

- Make sure all dependencies are installed before running the notebook.
- If you encounter any issues, refer to the assignment instructions and ensure you have followed all setup steps correctly.

## Detailed Description

### Components of the Project

1. **Game Environment**: The Connect 4 game environment supports game logic, player interactions, and visualizations using Pygame.
2. **AI Agents**: Various AI agents are implemented, including:
   - `human`: A human player making moves through input.
   - `randomAI`: An AI that makes random valid moves.
   - `stupidAI`: An AI with a predefined move priority.
   - `minimaxAI`: An AI using the Minimax algorithm.
   - `alphaBetaAI`: An AI using Alpha-Beta pruning.
   - `monteCarloAI`: An AI using Monte Carlo simulations.
3. **Simulation Script**: The `main.py` script sets up games between different AI agents and runs them. The `run.sh` script automates running multiple games and collects results.

### Significance of the Project

Implementing and evaluating different AI agents for Connect 4 provides a practical application of AI and reinforcement learning techniques. This project emphasizes:

- **AI Strategy Development**: Developing and testing various AI strategies for game playing.
- **Game Simulation**: Creating a robust game simulation environment.
- **Performance Evaluation**: Running multiple simulations to evaluate the performance of different AI agents.