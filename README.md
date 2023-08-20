# Number Guessing Game

This is a simple number guessing game implemented in Python. The game uses a unique card-based method to guess a number chosen by the player. It's a fun way to introduce players to binary representation concepts.

## How the Game Works

The game involves 6 cards, each containing a set of numbers. The first number on each card corresponds to a power of 2 in binary representation. The player thinks of a number between 1 and 63 and indicates whether their number exists on each card. The game then adds the corresponding first numbers on the selected cards to guess the player's number.

## Instructions

1. Click the "Open in Colab" button above to open the notebook in Google Colab.
2. Run the `number_guessing_game.py` script in your preferred Python environment.
3. The game will display the card numbers and contents.
4. Think of a number between 1 and 63 and type 'start' to begin.
5. Indicate whether your number exists on each card using 'yes' or 'no'.
6. The computer will guess your number based on your responses.
