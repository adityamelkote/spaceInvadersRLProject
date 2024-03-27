# spaceInvadersRLProject
## Abstract
This project explores various neural network training methodologies for autonomously playing the Atari game Space Invaders. We replicate the Deep Q-Learning approach and experiment with Vision Transformers and Dueling Network Architecture to enhance game performance.

## Introduction
Building upon the original "Playing Atari with Deep Reinforcement Learning" paper, we aim to improve the performance of agents playing Space Invaders using different deep learning strategies.

## Methods
- **Deep-Q Network Baseline**: Replication of the DQN architecture with modified hyperparameters for faster training.
- **Dueling Network for DQN**: Implementation of a dueling network architecture to predict state value and action advantage functions.
- **Vision Transformer**: Imitation learning using a Vision Transformer trained on human gameplay data to predict in-game actions.

## Results
Our experiments resulted in varied success across methodologies, with insights into the potential and limitations of each approach. The Vision Transformer showed effectiveness in imitation learning, and the modified DQN achieved better results within a shorter training period.

## Requirements
Requirements can be installed through Poetry
