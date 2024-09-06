# Reinforcement Learning Project

This repository contains assignments for a course on **CS6700-Reinforcement-Learning**. Each assignment focuses on implementing and understanding different reinforcement learning algorithms applied to classic control problems.

## Assignments Overview

1. **Acrobot DQN**: Implementation of the Deep-Q Network (DQN) algorithm to solve the Acrobot problem.
2. **Cartpole Actor-Critic**: Application of both one-step and n-step Actor-Critic algorithms on the Cartpole environment.
3. **Taxi SMDP Intra-Option Q-learning**: Solve the Taxi problem using Semi-Markov Decision Processes (SMDP) and Intra-Option Q-learning, with visualization via heat maps.

---

## Assignment Details

### 1. Acrobot DQN
- **Description**: Solve the Acrobot environment using the **Deep-Q Network (DQN)** algorithm. The objective is to learn an optimal policy to swing the lower link of a two-link robot to a height equal to the top link.
- **Key Concepts**: Deep learning, Q-learning
- **Environment**: Acrobot-v1 (OpenAI Gym)

[Acrobot DQN Implementation](/CS6700-Reinforcement-Learning/Assignments/Acrobot_DQN.ipynb)

---

### 2. Cartpole Actor-Critic
- **Description**: Apply both **one-step** and **n-step Actor-Critic** algorithms to the Cartpole environment, where the agent must balance a pole on a cart by controlling its movement. These algorithms optimize both the actor (policy) and critic (value) functions to improve the agent's performance.
- **Key Concepts**: Policy gradients, temporal difference learning, one-step and n-step returns, Actor-Critic.
- **Environment**: CartPole-v1 (OpenAI Gym)

[Cartpole Actor-Critic Implementation](/CS6700-Reinforcement-Learning/Assignments/Cartpole_Actor-Critic.ipynb)

---

### 3. Taxi SMDP Intra-Option Q-learning
- **Description**: Solve the Taxi-v3 environment using **Semi-Markov Decision Processes (SMDP)** and **Intra-Option Q-learning**. The task involves picking up and dropping off passengers at the correct locations, with intra-option learning applied to optimize long-term policies. The results are visualized with **heat maps** showing the value function.
- **Key Concepts**: Temporal abstraction, options framework, intra-option learning, SMDP, heat map visualization.
- **Environment**: Taxi-v3 (OpenAI Gym)

[Taxi SMDP Intra-Option Q-learning Implementation](/CS6700-Reinforcement-Learning/Assignments/Taxi_Qlearning.ipynb)

---