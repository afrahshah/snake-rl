# Snake AI with Reinforcement Learning

This project involves training a reinforcement learning agent to play the Snake game. The agent uses a Deep Q-Network (DQN) to learn optimal strategies and improve its performance over time.

## Project Demonstration

### During Training
![During Training](https://github.com/afrahshah/snake-rl/raw/c513609eddc40bc0b8d924afc0937243836b8199/Screenshot%202024-08-23%20121651.png)

### During Training
![During Training](
https://github.com/afrahshah/snake-rl/raw/c513609eddc40bc0b8d924afc0937243836b8199/Screenshot%202024-08-21%20103245.png)


## Project Structure

- **`game.py`**: Contains the implementation of the Snake game, including the game logic and rendering.
- **`helper.py`**: Includes helper functions, such as plotting results.
- **`model.py`**: Defines the neural network architecture for the Q-Network and the QTrainer class for training.
- **`agent.py`**: Implements the reinforcement learning agent, including methods for training, saving, and loading the model.
- **`arial.ttf`**: A font file used for rendering text in the game.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/snake-ai.git
   cd snake-ai
2. **Install dependencies**
   ```bash
   pip install torch numpy pygame matplotlib

## Usage
   ### Training the Agent
   To start training the agent, run the following command:
   
   `ls -l`

    python agent.py
    
The training script will:

Initialize the game and the agent.
Train the agent through multiple games.
Save the model state after training.

## Happy coding!
