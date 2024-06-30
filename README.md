# Teeko Game

This repository contains a Python implementation of the Teeko game with an AI player.

## Overview

Teeko is a two-player board game where players take turns placing and moving their pieces on a 5x5 grid, aiming to get four pieces in a row horizontally, vertically, or diagonally, or in a 2x2 square.

## How to Play

### Game Rules

1. **Drop Phase**:
   - Each player takes turns placing one of their pieces on any empty spot on the board.
   - The drop phase continues until each player has placed all four of their pieces.

2. **Move Phase**:
   - Once all pieces are placed, players take turns moving their pieces.
   - A piece can be moved to any adjacent empty spot (horizontally, vertically, or diagonally).

3. **Winning Condition**:
   - The first player to get four pieces in a row horizontally, vertically, diagonally, or in a 2x2 box wins the game.

### AI Implementation

The AI uses a minimax algorithm with a heuristic evaluation function to determine the best move. It evaluates the game state up to a certain depth to decide on the optimal move.

## Getting Started

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/imharshk18/teeko_game.git
   cd teeko_game
   
   
2. (OPTIONAL): Create and activate a virtual environment:

  ```sh
  python -m venv venv
  source venv/bin/activate  # On Windows use `venv\Scripts\activate`
  ```
  
### Running the game
To run the game, execute the following command:
```sh
python teeko_game.py
```

### Gameplay
- The AI will randomly choose to play as either red ('r') or black ('b').
- During the drop phase, the AI and the player will take turns placing their pieces.
- During the move phase, the AI and the player will take turns moving their pieces.
- Input your moves in the format B3, where B is the column and 3 is the row.
- The game will indicate if there is a winner after each move.

### Example
```sh
Hello, this is Samaritan
0:       # Initial board state
1:       
2:       
3:       
4:       
   A B C D E
```

### Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

### License
This `README.md` file provides an overview of the game, instructions on how to install and run it, and an example of gameplay.




   
