# 🐢 Turtle Crossing Game

A Python arcade game where you guide a turtle safely across a busy road — without getting hit! Built with Python's `turtle` graphics library.

## Gameplay

Navigate your turtle from the bottom of the screen to the top while dodging oncoming cars. Each successful crossing advances you to the next level, where cars move faster. One collision and it's game over!

## Controls

| Key | Action |
|-----|--------|
| `↑` | Move turtle forward |

## Getting Started

### Prerequisites

- Python 3.x (the `turtle` module is included in the standard library — no extra installs needed)


## Project Structure

```
turtle-crossing/
├── main.py           # Game loop and collision detection
├── player.py         # Turtle player movement and finish line detection
├── car_manager.py    # Car spawning, movement, and speed scaling
├── scoreboard.py     # Level tracking and game over display
└── README.md
```

## Features

- Randomly spawning cars in a variety of colors
- Progressive difficulty — cars speed up with each level cleared
- Level counter displayed on screen
- Game over screen on collision
