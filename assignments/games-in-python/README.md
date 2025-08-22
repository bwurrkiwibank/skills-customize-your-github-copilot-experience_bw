

# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic Hangman word-guessing game in Python. Practice string manipulation, loops, conditionals, and random selection.

## 📝 Tasks

### 🛠️ Game Setup

#### Description
Create a Python program that sets up the Hangman game with a predefined list of words and randomly selects one for the player to guess.

#### Requirements
Completed program should:

- Contain a list of at least 5 words
- Randomly select one word for each game session
- Display the number of attempts allowed

### 🛠️ Gameplay Loop

#### Description
Implement the main game loop where the player guesses letters, and the program updates the display and tracks incorrect guesses.

#### Requirements
Completed program should:

- Accept single-letter guesses from the user
- Show current progress (e.g., _ a _ _ m a n)
- Track and display incorrect guesses remaining
- End when the word is guessed or attempts run out
- Display win or lose messages

#### Example
```python
Word: _ a n g m a n
Guesses left: 3
Guessed letters: a, n, g, m
```
