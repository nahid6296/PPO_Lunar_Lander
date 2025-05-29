# 🚀 PPO Agent for LunarLander-v3 (Gymnasium + PyTorch)

This repository contains a modular, organized implementation of the **Proximal Policy Optimization (PPO)** algorithm to train an agent to solve the [`LunarLander-v3`](https://www.gymlibrary.dev/environments/box2d/lunar_lander/) environment from OpenAI Gymnasium.

<p align="center">
  <img src="docs/lunar_lander.gif" alt="Lunar Lander PPO Demo" width="480"/>
</p>

---

## 🧠 Project Highlights

- ✅ PPO algorithm using PyTorch
- ✅ Modularized design: `model`, `ppo`, `train`, `evaluate`, `memory`
- ✅ Fully Colab-compatible
- ✅ Resumable training from checkpoints
- ✅ Automatic folder organization for multiple training runs
- ✅ Multi-episode video rendering (gameplay-style)
- ✅ Final reward plots for each run

---

## 🗂️ Folder Structure (Auto-created)

```text
Lunar_lander_Project/
├── run_1/
│   ├── weights/      ← PPO checkpoints every 50 episodes & final model
│   ├── plots/        ← Reward vs Episode training graph
│   └── videos/       ← Multi-episode gameplay video (rendered post-training)
├── run_2/
│   └── ...
