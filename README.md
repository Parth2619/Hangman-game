# 🎯 Hangman Game (Python CLI)

A fun and interactive command-line **Hangman** game built in Python! Test your guessing skills by trying to figure out the hidden word before you run out of lives.


## 🧠 How It Works

This game picks a random word from a list (`hangman_words.py`) and displays blanks for each letter. The player guesses one letter at a time. Correct guesses fill in the blanks, and wrong guesses cost lives.

Lose all your lives? Game over.  
Guess the word before that? You win!


## 🛠 Features

- Random word selection from a customizable list
- ASCII art visuals for the hangman and logo (from `hangman_art.py`)
- Tracks guessed letters and warns for repeats
- Displays remaining lives after each guess
- Victory and defeat messages with the correct word revealed



## 🧾 Project Structure

```bash
hangman/
├── hangman.py            # Main game logic
├── hangman_words.py      # Word list for random selection
└── hangman_art.py        # ASCII art for logo and hangman stages
```



## 📦 Requirements

- Python 3.x  
(No external libraries needed)



## ▶️ How to Play

1. Clone the repo or download the files.
2. Make sure `hangman.py`, `hangman_words.py`, and `hangman_art.py` are in the same directory.
3. Run the game:

```bash
python hangman.py
```



## ✍️ Example

```plaintext
****************************6 LIVES LEFT****************************
Guess a letter: e

Word to guess: _ e _ _ _

****************************5 LIVES LEFT****************************
You guessed x, that's not in the word. You lose a life.
```

ASCII hangman art will visually track your remaining lives.


## 💡 TODOs & Improvements

- Show previously guessed incorrect letters
- Option to play again after game over
- Difficulty levels (easy/medium/hard word lists)
- GUI version using Tkinter or a web framework

## 👨‍💻 Author

Made with 💻 and ☕ by Parth Koshti
