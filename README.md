# Guess the Number

A simple command-line game written in Rust where the user attempts to guess a randomly generated number between 1 and 50.

## Features

- Generates a random number using Rust's `rand` crate.
- Accepts user input and validates it.
- Provides hints if the guess is too high or too low.
- Notifies the user when they guess the number correctly.

## How to Run

### Prerequisites

Ensure you have the following installed:
- [Rust](https://www.rust-lang.org/tools/install) (latest stable version)

### Steps to Run the Program

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/guess-the-number.git
   cd guess-the-number
   ```

2. Build and run the program:
   ```bash
   cargo run
   ```

3. Follow the prompts in the terminal to play the game.

## How to Play

1. The program generates a random number between 1 and 50.
2. You will be prompted to guess the number.
3. After each guess, the program will provide feedback:
   - "The number guessed is greater": Your guess is too high.
   - "The number guessed is small": Your guess is too low.
   - "You Won!!": You guessed the number correctly.

4. Keep guessing until you find the correct number.

## Example Gameplay

```text
Guess the number!
Please input your guess:
25
You guessed 25
The number guessed is greater
Please input your guess:
10
You guessed 10
The number guessed is small
Please input your guess:
15
You guessed 15
You Won!!
```

## Dependencies

- [`rand`](https://crates.io/crates/rand): Used to generate the random number.

## Error Handling

- The program ensures input validation by handling cases where the user enters non-numeric input. If invalid input is provided, the program prompts the user to "Enter a valid input".

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contribution

Feel free to submit issues or create pull requests for any improvements or bug fixes.

---
