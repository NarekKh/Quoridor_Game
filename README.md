# Quoridor AI Project

## Overview
Quoridor is a strategic board game invented by Mirko Marchesi and first released in 1997. The game involves navigating a 9x9 grid while strategically placing walls to hinder opponents. It challenges both pathfinding and strategic thinking, making it an excellent test case for AI development.

This project focuses on creating an AI agent capable of playing Quoridor effectively using advanced algorithms such as Minimax with alpha-beta pruning and Monte Carlo Tree Search (MCTS).

## Features
- Supports 2-4 players with the same goal of reaching the opponent's territory first.
- Incorporates AI strategies for movement and wall placement.
- Adapts dynamically to opponent behavior.
- Implements both deterministic and probabilistic AI algorithms.

## AI Methodology
1. **Algorithms Used**:
   - **Minimax Algorithm**: Evaluates potential moves to optimize the AI's strategy while minimizing losses, enhanced with alpha-beta pruning to reduce computational overhead.
   - **Monte Carlo Tree Search (MCTS)**: Simulates multiple game scenarios to determine the best wall placements and paths.

2. **Heuristics and Adaptation**:
   - Dynamic evaluation of game states using a heuristic function.
   - Integration of movement and wall placement strategies based on game phases and opponent actions.

3. **Game State Representation**:
   - The 9x9 grid is represented as a 2D matrix, updated dynamically during gameplay.
   - Adaptive heuristics prioritize movement efficiency and strategic disruption of opponent paths.

4. **Evaluation Metrics**:
   - Win rate
   - Average moves per game
   - Strategic wall usage

## Evaluation Results
The AI was tested over 50 games against human opponents with varying strategies. Key findings include:
- **Win Rate**: 66%
- **Average Moves per Game**: 24
- **Walls Used per Game**: 8

The results demonstrate the AI's ability to adapt to different gameplay scenarios, with consistent performance across games. However, the AI showed limitations in complex multi-step planning against strategic opponents.

## Future Work
- Incorporation of neural network-based opponent modeling for improved adaptability.
- Real-time strategy adjustments for wall placement and movement.
- Difficulty scaling to accommodate varying player skill levels.
- Exploration of reinforcement learning techniques, including reward functions for dynamic strategy optimization.
