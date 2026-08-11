
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a text-based Hangman game in Python that uses strings, loops, conditionals, and user input to let players guess a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️ Word Selection and Guessing Logic

#### Description

Create the core Hangman gameplay by selecting a random word and allowing the player to submit letter guesses.

#### Requirements
Completed program should:

- Randomly choose a secret word from a predefined list of at least 5 words
- Prompt the player to enter a letter guess and validate the input
- Track letters that have been guessed correctly and incorrectly
- Update the displayed word state using underscores for hidden letters

### 🛠️ Game Feedback and End Conditions

#### Description

Add player feedback, remaining attempts, and clear win/lose conditions to complete the Hangman experience.

#### Requirements
Completed program should:

- Show the current progress of the word after every guess
- Display previously guessed letters that were incorrect
- Track and display the remaining number of incorrect guesses allowed
- End the game with a win message when the word is fully guessed or a lose message when attempts are exhausted
- Reveal the secret word when the game ends
