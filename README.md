# Reinforcement-Learning-HighwayEnv

This project aimed to solve the highway-fast-v0 and racetrack-v0 environments from the HighwayEnv library using reinforcement learning (RL) techniques. In the highway-fast-v0 environment, an agent needs to navigate a highway while avoiding collisions and optimizing its speed. We experimented with several RL algorithms, including PPO, DQN, and A2C from Stable-Baselines3, as well as a custom implementation of Double DQN combined with Dueling. The performance of each model was evaluated based on reward averages, and hyperparameter tuning was conducted using Optuna to optimize PPO.

In the racetrack-v0 environment, the challenge was to navigate a race track efficiently without crashing, using visual data to inform the agent's decisions. The PPO algorithm with a custom CNN architecture was applied, demonstrating strong performance, though with some variability. The project allowed for a deep dive into RL techniques, providing valuable experience in algorithm comparison, hyperparameter optimization, and real-time performance monitoring.

Through these experiments, I gained a comprehensive understanding of RL in dynamic environments and enhanced my practical skills for tackling real-world problems using reinforcement learning.

>Note: This project was made with time and hardware constraints. It presents areas for improvement and is therefore not perfect.

## Presentation of the results

A YouTube video presenting the results of each model used can be found here: **[Click on me](https://www.youtube.com/watch?v=stc9b9Tivr8)**

## Coding Solution

The complete solution can be found in the Jupyter notebook: **Reinforcement Learning HighwayEnv.ipynb**