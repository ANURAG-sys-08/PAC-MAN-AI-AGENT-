DCQN Pacman AI Agent
A Deep Convolutional Q-Network (DCQN) agent that learns to play Pacman using reinforcement learning.

Features
CNN-based Q-network for spatial state processing

Experience replay and target network for stable training

Epsilon-greedy policy for exploration

Trains to maximize score by eating pellets and avoiding ghosts

Installation
bash
Copy
Edit
cd dcqn-pacman
pip install -r requirements.txt
Usage
Train
bash
Copy
Edit
python train.py --episodes 1000
Evaluate
bash
Copy
Edit
python evaluate.py --model models/dcqn_pacman.pth --episodes 100
Project Structure
train.py — train the agent

evaluate.py — test the agent

src/ — code for model, replay buffer, agent

models/ — saved weights
