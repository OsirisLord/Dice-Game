# Dice-Game

## Overview

Dice-Game is a simple two-player dice game implemented using HTML, CSS, and JavaScript. The objective of the game is to be the first player to reach a score of 100 points.

## Game Rules

1. The game has two players, playing in rounds.
2. In each turn, a player rolls a dice as many times as they wish. Each result gets added to their CURRENT score.
3. If the player rolls a 1, all their CURRENT score gets lost. After that, it's the next player's turn.
4. The player can choose to 'Hold', which means that their CURRENT score gets added to their TOTAL score. After that, it's the next player's turn.
5. The first player to reach 100 points on their TOTAL score wins the game.

## Features

- Roll Dice: Players can roll the dice to accumulate points.
- Hold: Players can choose to hold their current score and add it to their total score.
- New Game: Players can start a new game at any time.
- Active Player Indicator: The UI clearly shows which player's turn it is.
- Winning State: The game ends and indicates the winner when a player reaches 100 points.

## Technical Details

- The game is built using vanilla JavaScript with DOM manipulation.
- It uses event listeners for user interactions (rolling dice, holding score, and starting a new game).
- The game state is managed using variables for scores, current player, and game status.
- CSS classes are used to visually represent the game state (active player, winner).

## How to Run

1. Clone the repository.
2. Open the `index.html` file in a web browser.

## Files

- `index.html`: The main HTML structure of the game.
- `style.css`: Contains all the styling for the game (not provided in the code snippet).
- `script.js`: Contains the JavaScript code for game logic and interactions.
