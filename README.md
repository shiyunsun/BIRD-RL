# Deep Q learning for Flappy Bird 🐤
This repository contains the implementation of a Deep Q Network (DQN) to play the Flappy Bird game. The DQN is a reinforcement learning algorithm that learns to play the game by interacting with the environment and updating its Q-values based on the observed rewards.Click [here](http://www.youtube.com/watch?v=9a1lPtSu9Fw) to see the full demo of the pre-trained agent achieving a score of 112

<img src="assets/FlappyBird_with_DQN.gif" alt="Alt text" style="width: 70%; height: 70%;">

# Environment
#### State space
- the last pipe's horizontal position
- the last top pipe's vertical position
- the last bottom pipe's vertical position
- the next pipe's horizontal position
- the next top pipe's vertical position
- the next bottom pipe's vertical position
- the next next pipe's horizontal position
- the next next top pipe's vertical position
- the next next bottom pipe's vertical position
- player's vertical position
- player's vertical velocity
- player's rotation
#### Action space
0 - do nothing
1 - flap
#### Rewards
- +0.1 - every frame it stays alive
- +1.0 - successfully passing a pipe
- -1.0 - dying
# Deep Q Network 🕸️
<img src="assets/critic_network.png" alt="Alt text" style="width: 40%; height: 40%;"> <img src="assets/dqn.png" alt="Alt text" style="width: 40%; height: 40%;">
# Usage
# Reference
