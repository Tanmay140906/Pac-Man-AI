# Pac-Man AI: Search & Intelligent Decision-Making

An AI game-playing project exploring classical search algorithms, heuristic pathfinding, and multi-agent decision-making in a Pac-Man environment. The project demonstrates how intelligent agents navigate mazes, evaluate possible actions, and make strategic decisions in the presence of adversaries.

## Overview

The project applies fundamental AI techniques to solve navigation and game-playing problems. Agents can search for paths to objectives, evaluate alternative game states, and select actions based on their expected outcomes.

## Key Features

### 1. Search Algorithms
- **Depth-First Search (DFS):** Explores paths through the maze using backtracking.
- **Breadth-First Search (BFS):** Finds shortest paths in unweighted search spaces.
- **Uniform Cost Search (UCS):** Finds minimum-cost paths by prioritizing accumulated path cost.
- **A* Search:** Combines path cost with a heuristic estimate to guide the search toward a goal.

### 2. Multi-Agent Decision-Making
- **Minimax:** Evaluates possible future game states against adversarial opponents.
- **Alpha-Beta Pruning:** Reduces unnecessary search by pruning branches that cannot affect the final decision.
- **Expectimax:** Evaluates decisions under a probabilistic model of opponent actions.
- **Heuristic Evaluation:** Estimates the desirability of game states to support strategic action selection.

### 3. Reinforcement Learning
Includes a basic reinforcement-learning component for exploring reward-based decision-making and value estimation.

## How It Works

1. The agent observes the current game state.
2. It identifies available actions.
3. A search or decision-making algorithm evaluates possible outcomes.
4. The agent selects an action and updates its behavior based on the resulting state.

## Tech Stack

- **Language:** Python
- **Core concepts:** Graph search, heuristics, adversarial search, recursion, and decision-making

## Getting Started

Clone the repository:

```bash
git clone <your-repository-url>
cd <your-repository-directory>
```

Follow the instructions in the relevant project directory to run the game or execute the available tests.

## Learning Objectives

- Understand classical AI search and pathfinding.
- Apply heuristic functions to guide decision-making.
- Explore adversarial search and game-tree optimization.
- Compare alternative approaches to intelligent game playing.

## Scope

This version focuses on search algorithms, multi-agent decision-making, and basic reinforcement learning. Probabilistic ghost tracking has been excluded.
