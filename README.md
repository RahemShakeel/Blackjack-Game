# Blackjack Game

## Description
This is a simple console-based Blackjack game implemented in Python. The game allows a user to play against the computer, featuring card dealing, score calculation, and basic game logic. The objective is to get a score as close to 21 as possible without going over, and to beat the computer's score.

## Features
- **Card Dealing**: Randomly deals cards from a standard deck.
- **Score Calculation**: Computes scores and handles special cases such as Blackjack.
- **Game Logic**: Includes options to "hit" or "hold" and determines the winner based on game rules.
- **Interactive Gameplay**: Provides prompts for user input and displays game status.

## Requirements
- Python 3.x

## Usage
Type 'hit' to draw another card.
Type 'hold' to stop drawing cards and finish your turn.
The game will automatically handle the computer's turn and display the results.

## Game Rules
- Blackjack: A hand consisting of two cards totaling 21 is a Blackjack and wins instantly.
- Score Calculation: Face cards are worth 10 points, Aces can be worth 1 or 11, and all other cards are worth their face value.
- Winning: The player wins if their score is higher than the computer's score without exceeding 21, or if the computer goes over 21. The player loses if they go over 21 or if the computer's score is higher and does not exceed 21.
