
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic Hangman game in Python to practice string manipulation, loops, conditionals, and user interaction.

## 📝 Tasks

### 🛠️ Create the Game Setup

#### Description
Set up a Hangman game that chooses a secret word and displays the player's progress.

#### Requirements
Completed program should:

- Create a list of words and randomly select one for each round
- Show the hidden word as underscores, such as `_ _ _ _ _`
- Keep track of guessed letters and remaining attempts
- Print a clear game status after each guess

### 🛠️ Handle Player Input

#### Description
Let the player guess letters and update the game state based on their input.

#### Requirements
Completed program should:

- Ask the user for a single letter guess
- Check whether the letter is in the secret word
- Reveal matching letters in the correct positions
- Prevent repeated guesses and inform the player if they already guessed that letter

### 🛠️ Determine Win or Loss

#### Description
Finish the game by checking whether the word has been fully guessed or the player has run out of attempts.

#### Requirements
Completed program should:

- Decrease the number of remaining attempts for incorrect guesses
- End the game when the player correctly guesses the whole word
- End the game when the player runs out of attempts
- Display a final message showing whether the player won or lost
