# Guess-Game

This project is a simple Bash script that challenges the user to guess the number of files in the current directory. The game continues until the correct guess is provided, with feedback given for each incorrect attempt.

## How to Run the Program

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Run the program by entering:
   ```bash
   bash guessinggame.sh
   ```

## Features

- Prompts the user to guess the number of files in the current directory.
- Provides feedback if the guess is too high or too low.
- Congratulates the user upon a correct guess.
- Utilizes a function, a loop, and conditional statements.

## Makefile

The `makefile` automates the creation of the `README.md` file. Running `make` generates the README with the following details:

- The project title.
- The date and time when `make` was executed.
- The number of lines of code in `guessinggame.sh`.

## Example Output

```text
Welcome to the Guessing Game!
How many files are in the current directory? Enter your guess: 5
Too low! Try again.
How many files are in the current directory? Enter your guess: 10
Too high! Try again.
How many files are in the current directory? Enter your guess: 7
Congratulations! You guessed it right.
