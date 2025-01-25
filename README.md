# Hangman Game in Python

## Description

This is a simple Python-based Hangman game where players try to guess a word by inputting letters. The game displays the word with placeholders (underscores) and gives the player a limited number of lives. Each incorrect guess reduces a life, and the game ends when the player either guesses the word or runs out of lives.

## Features
- Randomly selects a word from a word list.
- Displays a graphical representation of the hangman stages.
- Tracks the number of remaining lives.
- Prevents the player from guessing the same letter multiple times.
- Informs the player when a guessed letter is correct or incorrect.

## Technologies Used
- Python 3.x
- Random module for choosing words from a list
- Custom graphics stored in `hangman_art.py`

## How to Play
1. The game will randomly choose a word from a predefined list.
2. You need to guess a letter at a time.
3. If your guess is correct, the corresponding placeholder will be replaced with the guessed letter.
4. If your guess is incorrect, you will lose a life and a part of the hangman will be drawn.
5. The game ends when either all letters are guessed correctly (you win) or you run out of lives (you lose).

## Files
- `hangman_game.py`: Main game logic, where the game is played.
- `hangman_words.py`: Contains a list of words used in the game.
- `hangman_art.py`: Contains the hangman stages and logo.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hangman-game.git
