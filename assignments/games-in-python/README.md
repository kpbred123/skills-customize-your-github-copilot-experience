# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a playable Hangman game using Python strings, loops, conditionals, and user input. Practice tracking game state as the player guesses letters in a randomly selected word.

## 📝 Tasks

### 🛠️ Set Up the Game

#### Description
Use the provided list of words to choose a secret word and initialize the variables needed to track the player's guesses and remaining attempts.

#### Requirements
Completed program should:

- Randomly select one word from the provided word list.
- Track the letters the player has guessed.
- Set and track a maximum number of incorrect guesses.

### 🛠️ Implement the Guessing Loop

#### Description
Create the main game loop so the player can guess letters, see their progress, and continue until they win or run out of attempts.

#### Requirements
Completed program should:

- Display each letter in the secret word as a letter if guessed or an underscore if not guessed (for example, `_ _ _`).
- Prompt the player for a letter and update the game state for correct and incorrect guesses.
- End when the player has guessed the word or used all allowed incorrect guesses.
- Display a clear win or lose message when the game ends.
