# 🐦 Flappy Bird AI - Deep Learning Agent

An AI-powered Flappy Bird game that uses deep reinforcement learning to master the game! Watch as the neural network learns to navigate through pipes with superhuman precision. 🎮✨

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-red)](https://pytorch.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## 🚀 Overview

This project implements a Deep Q-Network (DQN) agent that learns to play Flappy Bird through reinforcement learning. The AI starts with no knowledge of the game and gradually improves its performance through trial and error, eventually achieving scores that surpass human capabilities!

## ✨ Features

- 🤖 **Deep Q-Learning** implementation with experience replay
- 🎯 **Custom game environment** built with Pygame
- 📊 **Training visualization** to monitor the AI's progress
- 💾 **Model checkpointing** to save and resume training
- 🎮 **Human play mode** to compare your skills against the AI

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/boyyey/flappy-bird-ai.git
   cd flappy-bird-ai
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## 🧠 How It Works

The AI uses a **Deep Q-Network (DQN)** which:
- Takes the game state as input (bird position, pipe distances, etc.)
- Outputs Q-values for each possible action (flap or do nothing)
- Learns through reward feedback (+1 for passing pipes, -1000 for crashing)
- Uses experience replay to learn from past experiences

## 📈 Results

After training for X episodes, the AI typically:
- Achieves an average score of Y
- Can play indefinitely without crashing
- Develops strategies to optimize its path through pipes

## 🗂️ Project Structure

```
flappy-bird-ai/
├── models/           # Saved model weights
├── src/
│   ├── game.py      # Flappy Bird game implementation
│   ├── agent.py     # DQN agent definition
│   ├── train.py     # Training script
│   └── play.py      # Play script
├── requirements.txt  # Python dependencies
└── README.md        # This file
```

## 🛠️ Dependencies

- Python 3.8+
- PyTorch
- Pygame
- NumPy
- Matplotlib (for visualization)

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs 🐛
- Suggest new features 💡
- Submit pull requests 🔄

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the original Flappy Bird game
- Built using PyTorch for deep learning
- Game implementation based on Pygame

---

**Happy flapping!** 🐦➡️🎯

*If you enjoy this project, please give it a ⭐ on GitHub!*
