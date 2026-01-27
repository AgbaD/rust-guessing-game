# Guessing Game

A simple command-line number guessing game written in Rust.

## How It Works

1. The program generates a random secret number between 1 and 100
2. You enter guesses and receive feedback:
   - "Too small!" - your guess is below the secret number
   - "Too big!" - your guess is above the secret number
   - "You win!" - you guessed correctly
3. The game continues until you guess the correct number

## Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) (1.56 or later)

## Running the Game

```bash
cargo run
```

## Dependencies

- `rand` - for random number generation
