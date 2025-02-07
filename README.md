# 🎮 Hangman Game

## 📌 Description
Hangman is a classic word-guessing game where the player tries to guess a hidden word by guessing one letter at a time. The player has a limited number of attempts (lives), and for every incorrect guess, a part of the hangman is drawn. The game ends when the player either correctly guesses the word or loses all their lives.

## 🛠 Features
✅ Randomly selects a word from a predefined list  
✅ ASCII art representation of the Hangman  
✅ Keeps track of correctly guessed letters  
✅ Ends the game when the player wins or loses  

## 📋 Rules
- The player has **6 lives**.
- The player guesses one letter at a time.
- If the letter exists in the word, it is revealed.
- If the letter is incorrect, the player loses a life.
- The game ends when:
  - The player correctly guesses the entire word (**Win** 🎉).
  - The player runs out of lives (**Lose** ❌).

## 🖥 Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Hangman_Game.git
   cd Hangman_Game
   
2. Run the Python script:
   ```bash
   python hangman.py
## 🔡 Example Gameplay
   ```markdown
   _ _ _ _ _
   Guess a letter: a
   _ _ a _ a
    +---+
    |   |
    O   |
   /|\  |
   /    |
        |
   =========

   Guess a letter: b
   b a _ a b a
   You Won! 🎉
