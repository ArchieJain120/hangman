Hangman — Unix-Based Word Guessing Game

A command-line Hangman game built for Unix/Linux environments. The game allows players to guess words from multiple categories, including English words, English movies, and Bollywood movies.

Features
🎮 Interactive terminal-based gameplay
📚 Multiple word categories:
English Words
English Movies
Bollywood Movies
🔤 Letter-by-letter guessing
❤️ Limited number of incorrect attempts
🔄 Random word selection
🖥️ Designed for Unix/Linux terminals
⌨️ Simple keyboard-based controls
Categories

The game provides three categories to choose from:

English Words

General English vocabulary ranging from common to moderately difficult words.

English Movies

Titles of popular English-language movies.

Bollywood Movies

Titles of popular Hindi/Bollywood movies.

How to Run
1. Clone the repository
git clone <repository-url>
cd hangman
2. Compile

If the project is written in C:

gcc hangman.c -o hangman
3. Run
./hangman
How to Play
Start the game.
Select a category.
A random word/movie title is selected.
The word is initially hidden:
_ _ _ _ _ _
Enter one letter at a time.
If the letter exists in the word, its position is revealed.
Incorrect guesses reduce the number of remaining attempts.
Guess the complete word before running out of attempts to win.
