This is a Python implementation of the classic game Flappy Bird using the NEAT (Neural Evolution of Augmenting Topologies) algorithm to train a neural network to play the game. The AI learns to navigate through the game by jumping and avoiding obstacles.
Features
AI-Controlled Bird: The AI uses a neural network to determine when to jump, allowing it to adapt to the game environment and improve its performance over time.
Real-time Game Simulation: The game is simulated in real-time, with the AI making decisions based on the current state of the game.
Evolutionary Algorithm: The NEAT algorithm is used to evolve the neural network, allowing it to adapt and improve over generations.How to Run
Install Required Libraries:
neat (Neural Evolution of Augmenting Topologies)
pygame (for game simulation)
pickle (for saving and loading the best genome)
Run the Script:
python flappy_bird.pyConfiguration
The configuration file (config-feedforward.txt) is used to specify the parameters for the NEAT algorithm. This includes the population size, number of generations, and other settings.
Output
The script will output the best genome found during the simulation, along with the final statistics.
Note
This project is a basic implementation of the AI Flappy Bird game and can be improved by adjusting the configuration parameters, experimenting with different neural network architectures, or incorporating additional features.
