by Yogesh.Makvana

# Egg Catcher Game

**Egg Catcher** is a simple arcade-style game written in Python using the `Tkinter` library for graphical interface. The player controls a catcher (represented as an arc) to catch falling eggs and score points. The game gets progressively harder as the player catches more eggs.

## Features
- Catch eggs falling from the top of the screen.
- Catcher moves left and right using the arrow keys.
- Eggs increase in speed and frequency as the score increases.
- The player has 3 lives; losing all lives results in a Game Over.
- Colorful eggs with random colors that fall at varying speeds.
- Real-time score and remaining lives displayed on the screen.

## Requirements

To run the game, you need to have Python installed on your machine with the following libraries:

- **Tkinter** (for the graphical user interface)

If you're using Python 3.x, Tkinter should be included by default. If it's not, you can install it using the following command:

```bash
pip install tk
```

## Installation

1. Clone or download this repository to your local machine.

```bash
git clone https://github.com/yourusername/egg-catcher-game.git
```

2. Navigate to the folder containing the `egg_catcher.py` file.

3. Run the game script using Python:

```bash
python egg_catcher.py
```

## How to Play

1. **Objective**: Catch as many eggs as possible to score points while avoiding dropping them. Each egg caught gives you points, and the game becomes progressively harder as the speed and frequency of falling eggs increase.
   
2. **Move the Catcher**: Use the **Left Arrow (←)** and **Right Arrow (→)** keys to move the catcher. The catcher moves within the bottom area of the screen.

3. **Eggs**: The eggs fall from the top of the screen, and you need to position the catcher beneath them to catch them. The more eggs you catch, the faster the eggs will fall.

4. **Lives**: You start with 3 lives. Each time you miss an egg, you lose a life. The game ends when you lose all your lives. 

5. **Game Over**: Once all lives are lost, a message will appear displaying your final score.

## Gameplay Controls

- **Left Arrow (←)**: Move the catcher left.
- **Right Arrow (→)**: Move the catcher right.

## Game Mechanics

- **Eggs**: Eggs randomly fall from the top of the screen. They come in various colors, which are cycled through randomly.
- **Score**: Each egg you catch increases your score by a fixed amount (10 points). As you catch more eggs, the game becomes harder, with the egg's falling speed and frequency increasing over time.
- **Lives**: You start with 3 lives. Losing an egg (i.e., the egg falls off the screen) results in the loss of one life. The game ends when no lives are remaining.

## Code Overview

- **Canvas**: The main graphical area where the game elements are drawn.
- **Catcher**: The arc that the player controls to catch the falling eggs.
- **Eggs**: These are drawn as ovals, which fall from the top to the bottom of the screen.
- **Score and Lives**: The current score and remaining lives are displayed in the top corners of the screen.
- **Game Logic**: The game creates new eggs, moves them down the screen, checks for collisions between the eggs and the catcher, and updates the score and lives accordingly.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

This `README.md` file provides instructions on how to install, play, and understand the core components of your Egg Catcher game. You can customize it further based on your personal preferences or specific project details.
