# Hangman

Console-based Hangman implementation with ASCII art for the gallows at each life stage, a banner, and a large built-in English word list.

## Requirements

- Python 3.8 or newer

## Run the game

```bash
python hangman.py
```

Gameplay highlights:

- A random word is picked from `word_list`.
- You guess one letter per turn; repeated guesses are ignored.
- Each incorrect guess advances to the next `stages` drawing.
- When the drawing is complete, the game ends in a loss; guessing the full word first ends in a win.

