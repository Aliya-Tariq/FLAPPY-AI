# FLAPPY-AI

THIS IS A AI VERSION OF THE CLASSIC FLAPPY BIRD GAME.
<br> THE AI PLAYS THE FLAPPY BIRD GAME AND LEARNS TO COORDINATE THE CONTROLLER.


# Features
AI-controlled gameplay: The game is played by an AI that learns how to avoid pipes.
Training with NEAT: The AI learns using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm.
Game environment: Real-time environment built with Pygame to simulate the Flappy Bird game.
Generational learning: The AI improves over multiple generations.
Save and load AI models: The best-trained AI model is saved and can be loaded for future use.
Score and performance tracking: Displays the current score, number of generations, and number of birds alive during training.
# Requirements
To run this project, you'll need the following Python libraries:

pygame: A set of Python modules used for writing video games.
neat-python: Python implementation of the NEAT algorithm for evolving neural networks.
You can install these libraries using pip:

bash
Copy code
pip install pygame neat-python
Make sure you have Python 3.6 or higher installed to run this project.

# Installation
1. Clone the repository
First, clone the repository to your local machine:

git clone https://github.com/yourusername/flappy-ai.git
cd flappy-ai

2. Install required libraries
After cloning the repository, install the necessary dependencies:

pip install -r requirements.txt

3. Run the game
To start the game and AI training, simply run the main program:

python flappy_ai.py

This will launch the game, where the AI starts training and playing.

# Usage
Start Training: When you run flappy_ai.py, the AI will start training using the NEAT algorithm. It will evolve over generations, with each generation aiming to improve the AI’s performance in the game.

Game Environment: As the AI trains, the game window will show the bird flying through pipes. The bird is controlled by the AI that learns over time how to avoid the pipes.

Monitor Training: During training, you can observe the following:

Score: The current score is displayed.
Generations: The number of generations that have passed is shown.
Birds Alive: The number of birds currently alive in the current generation is displayed.
Saving AI Models: Once training is complete, the AI's best-performing neural network is saved as a .pickle file, allowing you to load and run it in the future without retraining.

Optional Visualization: If you want to visualize the neural networks of the trained AI, you can enable the visualization feature by modifying the code.

# File Structure
```bash
flappy-ai/
│
├── flappy_ai.py           # Main game file with game logic and AI training
├── config-feedforward.txt # NEAT configuration file for the AI
├── imgs/                  # Directory for game assets (bird, pipe, background)
│   ├── bird1.png
│   ├── bird2.png
│   ├── bird3.png
│   ├── pipe.png
│   ├── base.png
│   └── bg.png
├── requirements.txt       # List of required libraries
└── README.md              # Project documentation

# Main Files:
  flappy_ai.py: Contains the game logic, AI training, and implementation of the NEAT algorithm.
  config-feedforward.txt: The NEAT configuration file that defines the parameters for the neural network evolution process.
  imgs/: Contains image assets used in the game for the bird, pipes, background, etc.
  requirements.txt: A file listing the necessary libraries for the project.

# Contributing
  If you'd like to contribute to this project, feel free to fork the repository and submit pull requests. Contributions could include:
  
  Enhancing the AI's performance.
  Adding more features to the game.
  Improving the documentation.
  Fixing bugs or improving code efficiency.
  # License
  This project is open-source and available under the MIT License. See the LICENSE file for more information.
  
  
