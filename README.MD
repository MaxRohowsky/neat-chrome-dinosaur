# NEAT Chrome Dino Game

![Preview](/preview.gif)
<br>
<br>

**A.I. Chrome Dinosaur Game** in **Python** using **Pygame** and **NEAT Algorithm**! 🦖

It's the game you see in the Chrome Browser, when you're offline - but with A.I. 

Made by [maxontech](https://twitter.com/max_on_tech)

## Table of contents

- [Description](#description)
- [YouTube Tutorial](#youtube-tutorial)
- [Installation](#installation)
- [Controls](#controls)
- [Libraries](#libraries)
- [Contact](#contact)

## Description

This is the **Chrome Dinosaur Game** using **NEAT** and **Pygame** written in **Python**. 
NEAT stands for neuro evolution of augmenting topologies and is a genetic algorithm that creates artificial neural networks.

In this project, NEAT is used to train an AI to play the Chrome Dinosaur Game.
The Chrome Dinosaur Game is a simple infinite runner where the player has to jump over cacti and avoid birds. 
The game gets progressively harder as the player's score increases. See how far your AI can run!


## YouTube Videos

1. [Python A.I. Tutorial (with NEAT) - Part 1 - Setup & Display Dinosaur](https://youtu.be/GKmD26lH51U)
2. [Python A.I. Tutorial (with NEAT) - Part 2 - Finishing the Game](https://youtu.be/K3IK1smbQuc)
3. [Python A.I. Tutorial (with NEAT) - Part 3 - Adding the A.I.](https://youtu.be/rDwaeXuQaEI)
4. [Python A.I. Tutorial (with NEAT) - Part 4 - Final Touches](https://youtu.be/6BZgNCnh8kc)

## Installation
Requirements: You must have [Python](https://www.python.org/downloads/) installed and preferably a code editor like [PyCharm](https://www.jetbrains.com/pycharm/download/).

1. Clone the repository 
2. In the terminal, navigate to the directory where the repository was cloned, e.g., `C:\Users\Max\PycharmProjects\neat-chrome-dinosaur`
3. Create a virtual environment, activate it, and install pygame by running the following commands in the terminal:
    ```bash
    python -m venv venv #This creates a virtual environment
    venv\Scripts\activate #This activates the virtual environment
    pip install -r requirements.txt #This installs the required libraries
    ```
4. Run the game by running the following command in the terminal:
    ```bash
    python main.py
    ```
Note on PyCharm: Often PyCharm detects the requirements and asks you to install them and create a virtual env. 
![Preview](/pycharm-requirements.PNG)

## Controls
- You don't need to control the dinosaur. The AI will do that for you :)

## Libraries

- [pygame](https://www.pygame.org/news): Pygame is a cross-platform set of Python modules designed for writing video games.
- [NEAT](https://neat-python.readthedocs.io/en/latest/): NEAT is a method developed by Kenneth O. Stanley for evolving arbitrary neural networks.

## Contact

Feel free to reach out to me [on Twitter](https://twitter.com/max_on_tech) if you have any questions or feedback! Hope you find this useful!