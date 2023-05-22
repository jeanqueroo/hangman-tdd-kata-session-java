# Hangman TDD Kata

Hangman is a word-guessing game where one player thinks of a word and the other player tries to guess it by suggesting letters. The word to be guessed is represented by a series of underscores, with each underscore representing a letter in the word.

The guessing player suggests letters one by one, and if the letter is present in the word, it is revealed in the correct positions.

However, if the letter is not part of the word, a part of a hangman's gallows is drawn.

The guessing player continues making guesses until they either guess the word correctly or the hangman drawing is completed, resulting in a loss. Hangman is a popular and fun word game often played with others.

For this Kata, we will simplify the game and focus on implementing it as a single-player game.

The following rules have been discussed for this session:

- Set up different levels of the game to determine the maximum number of guessing attempts:
    - Easy (60%)
    - Normal (40%)
    - Hard (20%)
- Calculate the maximum number of guessing attempts by rounding down the level-based percentage of the word length.
- Set the maximum number of guessing attempts when the next word is provided.
- Word repetition is not allowed.
- The game should have a word list from which the secret word will be chosen. The word list source will be a text file.
- The player will guess letter by letter to try to reveal the secret word.
- The secret word will be initially represented by a series of underscores.
- If the guessed letter is present in the word, it will be revealed in the correct positions.
- If the guessed letter is not part of the word, the number of remaining attempts will be reduced by one.

## Naming Template
When writing test cases, follow the following naming template:
`MethodName_WhenScenario_ThenExpectedResult`
## Git Managing guideline
- `RED -> Commit -> Green -> Commit Refactor -> Commit -> PR to kata-branch`
- [DEV WIP COMMITS](https://www.dmitriydubson.com/post/trunk-dev-wip-commits)

Feel free to explore and contribute to the development of the Hangman game using Test-Driven Development (TDD) principles during this session.

Let's have fun playing and improving the Hangman game together!