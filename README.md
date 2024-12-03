# MountainCar-v0 Deep Q-Learning

This project implements the **Deep Q-Learning** algorithm to solve the `MountainCar-v0` environment in OpenAI Gym. It trains an agent to solve the problem of pushing a car up a hill using reinforcement learning.

## Project Overview

- **Environment**: `MountainCar-v0` (OpenAI Gym)
- **Goal**: The goal is to train the car to reach the top of the hill in an environment where the car moves between two hills.
- **Algorithm**: The algorithm uses Deep Q-Learning (DQN) to approximate the state-action value function (Q-value) using a neural network.

## Installation

1. **Install Required Libraries**:
   To run this project, you will need to install the required libraries. You can do so by running the following command:

   ```bash
   pip install gym tensorflow numpy
