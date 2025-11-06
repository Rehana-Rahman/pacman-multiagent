# Pacman Multiagent Search

This project implements several intelligent agents for the classic Pacman game, using adversarial search and evaluation strategies. The code is designed to work in a command-line Python environment and has been tested and graded with the standard CS188 autograder.

## Implemented Agents

- **ReflexAgent:** Chooses actions based on an evaluation of immediate outcomes.
- **MinimaxAgent:** Uses the minimax algorithm to plan against adversarial ghosts.
- **AlphaBetaAgent:** Improves minimax search with alpha-beta pruning for efficiency.
- **ExpectimaxAgent:** Models ghost actions non-adversarially, using expectimax search.
- **Custom Evaluation Function:** A more advanced state evaluation for better decision making.

The repository also contains required files for autograding and project testing.

## Usage

Run agents in the terminal using Python:
```bash
python pacman.py -p MinimaxAgent -l smallClassic --no-graphics
python autograder.py
```

## Notes

- The project is Python-only and runs comfortably on most platforms, including Termux on Android.
- All temporary files (such as `__pycache__`) are excluded by `.gitignore`.

***


