# 📘 Assignment: Games in Python

## 🎯 Objective

Build a classic Hangman word-guessing game to practice Python strings, loops, conditionals, and user input handling while creating an engaging interactive experience.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Create the foundation for your Hangman game by setting up a word list and implementing random word selection functionality.

#### Requirements
Completed program should:

- Create a list of at least 5-10 words for the game
- Implement random word selection from the list
- Initialize game variables (attempts remaining, guessed letters, current progress)
- Display the word length using underscores (e.g., `_ _ _ _ _`)

### 🛠️ Game Logic and User Interaction

#### Description
Implement the core game loop that accepts player guesses, updates the game state, and provides feedback.

#### Requirements
Completed program should:

- Accept single letter guesses from the player
- Validate input (single letters only, no repeats)
- Update and display current progress showing correctly guessed letters
- Track and display incorrect guesses remaining
- Continue until the word is guessed or attempts are exhausted
- Display appropriate win/lose messages with the correct word revealed
