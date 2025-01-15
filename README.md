# Lunar Lander

This project implements a reinforcement learning agent to solve the **Lunar Lander** environment using **Deep Q-Learning (DQN)**. The agent learns to land a spacecraft on the surface of the Moon by interacting with the environment, observing the state, taking actions, and receiving rewards.

## Overview
The project involves training an agent to control the Lunar Lander in a simulated environment provided by OpenAI's **Gym**. The agent uses a **Deep Q-Network (DQN)** to make decisions and improve its performance over time by maximizing its cumulative rewards.

- **Environment**: Lunar Lander-v2 (provided by OpenAI Gym)
- **Reinforcement Learning Algorithm**: Deep Q-Learning (DQN)
- **Frameworks**: TensorFlow, Keras, Numpy

## Prerequisites
Ensure that the following libraries are installed:

- `numpy (vers 1.26.1)`
- `gym (vers 0.21.0)`
- `matplotlib`
- `tensorflow`

You can install them using the following command:

`pip install -r requirements.txt`

## Installation
Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/lunar_lander.git
   cd lunar_lander
   ```

## Usage
Run the main training script to start training the agent:

`python main_lunar_lander.py`

The agent will start training, and you'll see progress printed to the console along with scores for each episode.

## Acknowledgements
This project is built with the guide of Machine Learning with Phil youtube channel: https://www.youtube.com/watch?v=SMZfgeHFFcA&t=1269s

