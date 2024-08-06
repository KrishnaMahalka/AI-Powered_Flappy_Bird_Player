# AI-Powered Flappy Bird Game
Welcome to the AI-powered Flappy Bird game! This project integrates classic arcade gameplay with advanced AI techniques, using Pygame for the graphical interface and the NEAT (NeuroEvolution of Augmenting Topologies) algorithm to train an AI to master the game.
# Overview
Flappy Bird is a beloved arcade game where players navigate a bird through a series of pipes by tapping to flap its wings. This version of the game replaces human input with artificial intelligence. The AI, trained using NEAT, learns and evolves its strategy to improve performance and navigate through the pipes more effectively.

The primary goal of this project is to demonstrate the application of AI in gaming, showcasing how evolutionary algorithms can be used to develop intelligent agents that learn from their environment.

# Features

1. **Pygame Implementation**: The game’s graphical interface, including the bird, pipes, and scoring system, is created using Pygame. This library handles rendering, user input, and game logic.
2. **NEAT Algorithm**: Utilizes the NEAT algorithm to evolve neural networks capable of playing the game. NEAT evolves both the structure and weights of neural networks, allowing the AI to adapt and learn optimal strategies.
3. **AI Training**: The AI learns through a process of evolutionary adaptation. Over generations, the neural networks are refined based on their performance, leading to increasingly proficient gameplay.
4. **Customizable Parameters**:Users can adjust various settings related to the NEAT algorithm and game mechanics, including mutation rates, population size, and training duration. This flexibility allows experimentation and fine-tuning to improve the AI’s performance.
