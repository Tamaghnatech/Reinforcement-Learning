# Reinforcement Learning

This repository is dedicated to mastering the art and science of Reinforcement Learning (RL). From the basics of Markov Decision Processes to cutting-edge actor-critic methods, this repo explores how intelligent agents learn from interaction.

---

## 🧠 Topics Covered

### 🎮 Foundations
- Agent–Environment Interface
- Markov Decision Processes (MDPs)
- Rewards, Return, Episode, Value Functions
- Bellman Equations (Expectation and Optimality)

### 🧱 Dynamic Programming
- Policy Evaluation
- Policy Iteration
- Value Iteration

### 📊 Model-Free Methods

#### 1. **Monte Carlo (MC) Methods**
- First-visit vs Every-visit
- MC Prediction & Control
- Exploring Starts & ε-soft policies

#### 2. **Temporal Difference (TD) Learning**
- TD(0), SARSA, Q-Learning
- Expected SARSA
- TD(λ) and eligibility traces

### 🔁 Policy Gradient Methods
- REINFORCE algorithm
- Baseline subtraction and Variance Reduction
- Actor-Critic architectures
- Advantage Actor-Critic (A2C), A3C

### 🧠 Deep Reinforcement Learning
- Deep Q-Networks (DQN)
  - Experience Replay, Target Networks
- Double DQN, Dueling DQN, Prioritized Experience Replay
- Deep Deterministic Policy Gradient (DDPG)
- Twin Delayed DDPG (TD3)
- Soft Actor-Critic (SAC)

### 🤖 Exploration Strategies
- ε-greedy, Softmax
- Upper Confidence Bound (UCB)
- Thompson Sampling
- Intrinsic Motivation & Curiosity-Driven Learning

### 🌍 Multi-Agent RL & Game Theory
- Independent Q-Learning
- Self-play, Nash Equilibria, Minimax
- Cooperative & Competitive Agents

### 🧪 RL Theory & Stability
- Deadly Triad: Function Approximation, Bootstrapping, Off-policy
- Convergence guarantees (or lack thereof)
- Variance–Bias Trade-offs

---

## 📁 Folder Structure

- `notes/`  
  📚 Summaries, derivations of Bellman equations, theoretical notes on TD learning, and convergence properties.

- `projects/`  
  ⚙️ Implementations of:
  - Q-learning on GridWorld
  - Deep Q-Learning with OpenAI Gym (CartPole, MountainCar)
  - Policy gradient methods with PyTorch

- `diagrams/`  
  🧠 Visuals explaining:
  - MDP flows
  - Temporal difference updates
  - Policy vs Value-based algorithms
  - Actor–Critic architecture (Manim or draw.io)

---

## 🧰 Libraries & Environments
- [OpenAI Gym](https://www.gymlibrary.dev/)
- [PettingZoo (Multi-Agent)](https://www.pettingzoo.ml/)
- [RLlib (from Ray)](https://docs.ray.io/en/latest/rllib/)
- [Stable Baselines3](https://stable-baselines3.readthedocs.io/)
- [CleanRL](https://github.com/vwxyzjn/cleanrl)

---

## 🚀 Project Ideas
- Implement DQN with experience replay and compare to SARSA
- Create a custom Gym environment (e.g., GridWorld with teleport traps)
- Solve LunarLander-v2 using A2C and PPO
- Compare convergence of value iteration vs Q-learning
- Build an interactive RL visualizer for CartPole or Blackjack

---

May your agents explore efficiently,  
learn optimally,  
and converge with minimal regret.
