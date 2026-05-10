# Asteroids Game

A classic Asteroids arcade game built with Python and Pygame. Navigate your spaceship, destroy asteroids, and survive as long as you can.

![Python](https://img.shields.io/badge/python-3.13%2B-blue)
![Pygame](https://img.shields.io/badge/pygame-2.6.1-green)

## Controls

| Key | Action |
|-----|--------|
| W / S | Thrust forward / backward |
| A / D | Rotate left / right |
| Space | Fire |

## Setup

```bash
# Install dependencies
pip install .

# Run the game
python main.py
```

## Gameplay

- Destroy asteroids by shooting them. Large asteroids split into smaller ones.
- Avoid collisions with asteroids.
- The game ends on collision.

## Project Structure

```
asteroids-game/
├── main.py            # Game loop and initialization
├── player.py         # Player ship logic
├── asteroid.py       # Asteroid entity
├── asteroidfield.py  # Asteroid spawning
├── shot.py           # Bullet logic
├── circleshape.py    # Base shape class
├── constants.py      # Game configuration
└── logger.py         # Event logging
```
