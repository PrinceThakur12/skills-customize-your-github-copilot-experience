# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build the classic word-guessing game using Python strings, loops, and user input. Create a Hangman game where players guess letters to reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Set up the game by creating a function that randomly selects a word from a predefined list and initializes the game state.

#### Requirements
Completed program should:

- Define a list of words to choose from
- Randomly select one word at the start of the game
- Initialize variables to track guessed letters and remaining attempts
- Display the initial game state

### 🛠️ Guess Processing and Progress Display

#### Description
Implement the core game logic that processes player guesses and updates the game state accordingly.

#### Requirements
Completed program should:

- Accept letter guesses from the player
- Check if the guessed letter is in the word
- Update the display to show correct guesses in their positions (_ _ _ format)
- Track incorrect guesses and decrement remaining attempts
- Prevent duplicate guesses

### 🛠️ Game End Conditions and Messages

#### Description
Complete the game by implementing win/lose conditions and appropriate feedback messages.

#### Requirements
Completed program should:

- Display a win message when the word is completely guessed
- Display a lose message when attempts are exhausted
- Show the correct word when the game ends
- Allow the player to play again or exit
