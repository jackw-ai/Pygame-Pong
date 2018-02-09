# Pygame-Pong
Pong written with the Pygame library. Includes AI opponent and touchpad/mouse controls. The player plays against a very difficult AI opponent in a classic game of Pong.

## Installation
This game requires Python3 and Pygame to launch. Compatability with Python2 has not been tested.

To install Pygame, type the following terminal command.
```sh
python3 -m pip install pygame --user
```
## Launch
To launch this game, simply type
```sh
Python3 Pong.py
```
Doing so will launch a Pygame window that runs the game. 

## Controls
Control the paddle with your mouse or touchpad. Otherwise use the `W` or `UP` keys to move up and `S` or `DOWN` keys to move down.

## Rules
Successfully deflecting a ball will score one point, scoring a goal will score 5. The ball will reset to the middle and serve to the scorer upon a goal being scored.

