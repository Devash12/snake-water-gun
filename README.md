# Snake Water Gun Game

This is a simple implementation of the Snake Water Gun game (also known as Rock Paper Scissors) in Python.

## Description

The Snake Water Gun game is a hand game usually played between two people. In this implementation, the player competes against the computer. Each player chooses one of three options: Snake, Water, or Gun. The rules are:

- Snake defeats Water (Snake drinks Water)
- Water defeats Gun (Water douses Gun)
- Gun defeats Snake (Gun shoots Snake)
- If both players choose the same option, it's a tie

## How to Play

1. Run the Python script.
2. The computer will make its choice (hidden from the player).
3. You will be prompted to enter your choice:
   - Enter 's' for Snake
   - Enter 'w' for Water
   - Enter 'g' for Gun
4. The program will display both choices and announce the winner.

## Code Structure

- The game logic is implemented in the `gameWin` function.
- Random module is used for the computer's choice.
- User input is taken for the player's choice.
- The result is determined and displayed.

## Requirements

- Python 3.x
- Random module (part of Python's standard library)

## Running the Game

To play the game, run the Python script in a Python environment:

```
python snake_water_gun.py
```

or if you're using a Jupyter notebook, you can run the cell containing the code.

Enjoy playing Snake Water Gun!
