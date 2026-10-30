# Number Guessing Game

A simple command-line game written in Python. The computer picks a random number between 1 and 100, and you try to guess it in as few tries as possible.

## Features

- Random secret number from 1 to 100
- Hints after each guess ("Too low!" or "Too high!")
- Counts how many tries you took
- Handles invalid input (non-numbers) without crashing

## Requirements

- Python 3.6 or newer

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/number-guessing-game.git
   cd number-guessing-game
   ```

2. Run the game:

   ```bash
   python game.py
   ```

## How to Play

1. Start the game.
2. Type a number between 1 and 100 and press Enter.
3. Use the hints to narrow down your next guess.
4. Keep going until you find the secret number.

## Example

```
Guess the number between 1 and 100!
Your guess: 50
Too high!
Your guess: 25
Too low!
Your guess: 37
You got it in 3 tries!
```

## Project Structure

```
number-guessing-game/
├── game.py
└── README.md
```

## Contributing

Contributions are welcome. Feel free to open an issue or submit a pull request with ideas such as difficulty levels, a score board, or a limited number of attempts.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
