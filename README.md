# rl-agent-cartpole

# PPO CartPole Agent 🎮🧠

This project trains a reinforcement learning (RL) agent using **Proximal Policy Optimization (PPO)** to solve the classic **CartPole-v1** environment from OpenAI Gym. Implemented using Python and Stable-Baselines3 inside Jupyter Notebook.

## 📌 Problem Statement

CartPole is a classic control problem where the goal is to balance a pole on a moving cart using reinforcement learning. The agent receives rewards for keeping the pole upright as long as possible.

## 🚀 What This Project Does

- Builds a PPO agent using `stable-baselines3`
- Trains the agent on CartPole-v1 for 10,000 timesteps
- Saves the trained model as a `.zip` file
- Tests the model and renders the agent's actions

## 🛠️ Tech Stack

- **Python**
- **Gymnasium** (CartPole-v1 environment)
- **Stable-Baselines3** (PPO algorithm)
- **Jupyter Notebook**
- **PyTorch**

## 📁 Project Files

- `ppo_cartpole_rl.ipynb` – Jupyter notebook containing full code (training, saving, testing)
- `ppo_cartpole_model.zip` – Trained PPO model

## 💡 How to Run the Project

### 1. Install Dependencies

```bash
pip install gymnasium[classic-control]
pip install stable-baselines3
pip install pyglet

