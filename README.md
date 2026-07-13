# Snake Game

A classic Snake game built with Python and Pygame.

## Features

- Smooth snake movement.
- Food spawning and score tracking.
- Collision detection with walls and the snake's body.
- Game over state and restart option.
- Clean, modular code structure.

## Tech Stack

- Python 3
- Pygame

## Project Structure

```text
snake-game/
├── README.md
├── pyproject.toml
├── src/
│   └── snake_game/
│       ├── __init__.py
│       ├── main.py
│       ├── game.py
│       ├── snake.py
│       ├── food.py
│       ├── settings.py
│       └── utils.py
├── assets/
│   ├── images/
│   └── sounds/
├── tests/
└── docs/
```

## Installation

1. Clone the repository:

```bash
git clone https://github.comhttps://github.com/Felipe-Magalhaes-A-Carneiro/snake-game/snake-game.git
cd snake-game
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
```

- Windows:

```bash
.venv\Scripts\activate
```

- macOS/Linux:

```bash
source .venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## How to Run

```bash
python -m src.snake_game.main
```

## Controls

- Arrow Up: Move up.
- Arrow Down: Move down.
- Arrow Left: Move left.
- Arrow Right: Move right.
- R: Restart after game over.
- Esc: Quit the game.

## Learning Goals

This project helped me practice:

- Game loop design.
- Object-oriented programming.
- Collision detection.
- State management.
- Modular project organization.

## Future Improvements

- Add difficulty levels.
- Add a start menu.
- Add sound effects and background music.
- Add high score saving.
- Add animations and polish.

## License

This project is licensed under the MIT License.