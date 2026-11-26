# Python Fruit Hangman Game

A console-based **Hangman** word-guessing game built in Python using a Jupyter Notebook (`random` module, loops, dictionaries, and string/list manipulation).

## Features
* **Difficulty Levels:** Choose between `easy`, `medium`, and `hard` modes with progressively longer and trickier fruit names (including multi-word entries like *dragon fruit* and *passion fruit*).
* **Dynamic Attempt Limit:** Players get `word length + 2` guesses per round.
* **Live Progress Display:** Shows matched letters in their exact positions (`-` for unguessed letters) and checks for a win at the end of the round.
* **Replay Loop:** Lets the player choose whether to play another round or exit (`yes`/`no`).

## How to Run
1. Clone or download this repository.
2. Open the notebook (`hangman_game.ipynb`) in **Google Colab**, **Jupyter Notebook**, or **VS Code** with Python 3 installed.
3. Run the cells in order from top to bottom and enter your difficulty level and letter guesses in the prompt.

## Repository Contents
* `hangman_game.ipynb` — Interactive notebook containing the game rules, basic loop prototype, and difficulty-based `play()` function.
* `README.md` — Project overview and usage instructions.
