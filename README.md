# Tic-Tac-Toe Game with Pygame and Minimax AI

A simple Tic-Tac-Toe game implemented in Python using Pygame for the graphical interface and a Minimax algorithm for the AI opponent. This project is based on the CS50 AI Tic-Tac-Toe specification.

## Features

- Choose to play as **X** or **O** against the computer.
- Computer uses the Minimax algorithm for optimal play.
- Clean and intuitive Pygame-based UI.
- Option to play again after the game ends.

## Requirements

- Python 3.7 or higher (tested on Python 3.11)
- [Pygame](https://www.pygame.org/) library
- `OpenSans-Regular.ttf` font file in the project root (or adjust fonts in code)

## Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. **Install dependencies**  
   ```bash
   pip install pygame
   ```

3. **Ensure font file**  
   Place `OpenSans-Regular.ttf` in the root directory, or modify `runner.py` to use a font available on your system.

## Usage

Run the main script to start the game:
```bash
python runner.py
```  
- Click **Play as X** or **Play as O** to begin.
- Click on an empty cell to make your move.
- The computer will move automatically.
- After game over, click **Play Again** to restart.

## Project Structure

```
.
├── runner.py            # Main game loop & Pygame UI
├── tictactoe.py         # Game logic (initial state, Minimax, utility functions)
├── OpenSans-Regular.ttf # Font file for UI text
└── README.md            # This documentation
```

## Contributing

Contributions are welcome! Feel free to:

- Open issues for bugs or feature requests.
- Submit pull requests for improvements or new features.

Please follow standard GitHub flow:
1. Fork the repository.  
2. Create a feature branch.  
3. Commit your changes.  
4. Open a pull request.

## License

This project is released under the [MIT License](https://opensource.org/licenses/MIT).

---

*Enjoy playing!*
