# Memory Game

This is a classic Memory Game built using JavaScript, CSS, and HTML. The objective of the game is to match pairs of cards by flipping them. The game features a splash screen for entering the player's name, sound effects for interactions, and a mechanism to prevent clicking while cards are being checked for matches.

## Features

* Prompt for player’s name
* Interactive UI with card flip animations
* Sound effects for successful and failed matches
* Shuffle mechanism to randomize card positions
* Visual indication of matched cards
* Count of attempts to find matches

## How to Play

1. Open the game in your browser.
2. Enter your name when prompted.
3. The game starts by showing all cards for a brief moment and then hiding them.
4. Click on any two cards to flip them.
5. If the two flipped cards match, they remain visible and are marked as matched.
6. If the cards do not match, they are flipped back over.
7. The game ends when all cards are matched.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/memory-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd memory-game
   ```
3. Open `index.html` in your preferred web browser to play the game.

## Code Explanation

### HTML

The game’s HTML structure includes:
* A splash screen for entering the player's name
* A game container for the memory cards
* Elements to display the player’s name and the number of attempts

### CSS

The CSS file styles the game board, cards, and various game states such as flipped cards and matched cards. It also includes animations for the card flips.

### JavaScript

The JavaScript file handles:
* Prompting for the player's name and updating the UI
* Flipping cards and checking for matches
* Preventing interaction while checking matches
* Shuffling cards at the start of the game
* Updating the number of attempts

### Key Functions

* `flipBlock(selectedBlock)`: Adds the 'is-flipped' class to the selected block and checks for matches if two blocks are flipped.
* `stopClicking()`: Prevents clicking while two blocks are being checked for a match.
* `checkMathedBlocks(firstBlock, secondBlock)`: Checks if the two flipped blocks match and updates their state accordingly.
* `shuffle(array)`: Shuffles the array of card positions to randomize the game board.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

