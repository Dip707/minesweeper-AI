# Minesweeper AI

![build-passing](https://img.shields.io/badge/Build-passing-success?style=flat-square)
![test-passing](https://img.shields.io/badge/Tests-passing-success?style=flat-square)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-informational?style=flat-square)](https://www.python.org/)
[![made-with-pygame](https://img.shields.io/badge/Made%20With-Pygame-informational?style=flat-square)](https://www.pygame.org/)

Minesweeper AI is an implementation of the classic Minesweeper game, featuring a built-in AI agent to assist or automatically play the game. The game is built using Python and Pygame.

## Screenshots

### Autoplay with Inference Shown (GIF - 25 seconds)

<p align="center">
<img src="assets/gui/autoplay.gif" alt="Autoplay"/>
</p>

### Main Menu

<p align="center">
<img src="assets/gui/main-menu.png" alt="Main Menu"/>
</p>

### Start Screen

<p align="center">
<img src="assets/gui/start-screen.png" alt="Start Screen"/>
</p>

### Gameplay with Inference Hidden

<p align="center">
<img src="assets/gui/gameplay.png" alt="Gameplay"/>
</p>

### Gameplay with Inference Shown

<p align="center">
<img src="assets/gui/gameplay-inference.png" alt="Gameplay with Inference Shown"/>
</p>

## Features

- Classic Minesweeper gameplay with adjustable board dimensions and mine count
- AI agent to assist with gameplay or autoplay
- Autoplay speed control
- Option to show or hide AI's inference on safe and mine cells
- Attractive and responsive user interface

## Installation

1. Install Python 3.7 or later from [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Clone this repository or download and extract the ZIP file
3. Install the required dependencies: `pip install pygame`
4. Run the game: `python Runner.py`

## How to Play

- Left-click on a cell to reveal it
- Right-click on a cell to flag it as a mine
- Use the buttons on the right side to control AI and game settings
- Win the game by flagging all mines correctly

## AI Features

- The AI agent can make safe moves and random moves based on its knowledge
- The agent can mark cells as safe or as mines, and updates its knowledge accordingly
- The agent can infer new knowledge from existing knowledge, improving its performance
- Autoplay mode allows the AI agent to play the game automatically with adjustable speed

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue to discuss potential changes or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.