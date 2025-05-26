# hangman
# 🎯 Hangman - Python Terminal Game

This is a classic **Hangman** game built with Python, played directly in the terminal. The player tries to guess a hidden word letter by letter. Every incorrect guess brings the stickman one step closer to being fully "hanged."

## 🧠 Game Rules

- A random word is selected at the start.
- The player has **6 lives**.
- Each incorrect guess reduces the number of lives.
- Correct guesses reveal letters in their correct positions.
- If you guess the full word before running out of lives, you win!
- If you run out of lives, the game ends and the word is revealed.

## 🗂️ Project Structure

This game consists of 3 Python files:

- `hangman.py` → Main game logic
- `hangman_words.py` → Contains a list of possible words (e.g., `word_list = ["python", "hangman", "developer"]`)
- `hangman_art.py` → Contains ASCII art for game stages and the game logo


