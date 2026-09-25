# Snake, Water, Gun

A simple Python command-line game inspired by Rock-Paper-Scissors.

## How to Play

You play against the computer by choosing one of three options:
- **Snake (s)**
- **Water (w)**
- **Gun (g)**

The computer picks randomly, and the winner is decided based on these rules:
- 🐍 Snake drinks Water → Snake beats Water
- 💧 Water jams the Gun → Water beats Gun
- 🔫 Gun kills the Snake → Gun beats Snake

If both players pick the same option, it's a draw.

## Running the Game

```bash
python main.py
```

You'll be prompted to enter your choice (`s`, `w`, or `g`), and the result will be printed immediately.

## Example
Enter your choice: s
You chose Snake
Computer chose Water
You win!

## Tech Used
- Python 3
- Built-in `random` module

## About

This is a small practice project exploring conditional logic and randomness in Python.
