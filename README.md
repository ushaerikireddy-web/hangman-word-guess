# hangman-word-guess

A simple terminal/console-based Hangman (word-guess) game written in Python.  
The game picks a random word from a predefined list and lets the player guess it one letter at a time.  

---

## 🎯 Features

- Random word selection from a word list.  
- Letter-by-letter guessing.  
- Tracks correct and incorrect guesses.  
- Prevents repeated guesses of the same letter.  
- Displays progress: shows which letters are revealed and which remain hidden until guessed.  
- Handles win and lose conditions (win when all letters are guessed; lose when guessing limit reached).  

---

## 📁 Project Structure

## 📁 Project Structure

```
hangman-word-guess/
├── main_game.py       # Main script to run the game
├── visuals.py         # Handles ASCII art (optional)
├── words_list.py      # Contains the list of possible words
└── README.md          # Documentation file
```


---

## 🛠️ How to Run

1. Make sure you have Python 3.x installed.  
2. Clone or download the repository.  
3. In a terminal, run:

```bash
python main_game.py
 ```
4.Follow the on-screen prompts to guess letters and try to guess the word before running out of attempts.

## ✅ Game Rules

● You’ll see underscores representing each letter of the hidden word.

● Enter one letter at a time as your guess.

● If the letter is in the word, all occurrences are revealed.

● If not, it counts as a wrong guess.

● Re-guessing a letter that you’ve already tried will not count (or will prompt you accordingly).

● The game ends when either you guess all letters correctly (win), or you reach the maximum allowed wrong guesses (lose).

## 🎓 Why This Project

● This project is a good exercise for beginners to learn:

● basic Python syntax (loops, conditionals, functions),

● working with lists and strings,

● handling user input,

● simple game logic and control flow flow.

## 🚀 Future Improvements (Ideas)

● Add difficulty levels (e.g., easy / medium / hard word lists).

● Add support for phrases instead of just single words.

● Improve the UI: display ASCII-art of a hanging man as wrong guesses accumulate.

● Add option to guess the full word at once (instead of one letter at a time).

● Save high-scores (e.g., number of wins / losses).
