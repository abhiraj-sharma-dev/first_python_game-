# first_python_game-
A Number guessing game using python languague.
# Number Guessing Game 🎯

A simple Python-based Number Guessing Game where the computer randomly selects a number between 1 and 100, and the player tries to guess it.

## Features

* Random number generation between 1 and 100
* Hints to guide the player:

  * "Higher number please" if the guess is too low
  * "Lower number please" if the guess is too high
* Counts the number of attempts taken to guess the correct number
* Beginner-friendly Python project

## How It Works

1. The program generates a random number between 1 and 100.
2. The user enters a guess.
3. The program provides feedback until the correct number is guessed.
4. Once guessed correctly, the program displays the number of attempts used.

## Technologies Used

* Python 3
* Random Module

## Code Example

```python
import random

n = random.randint(1,100)
```

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/number-guessing-game.git
```

2. Navigate to the project folder:

```bash
cd number-guessing-game
```

3. Run the program:

```bash
python main.py
```

## Sample Output

```text
Guess the number: 50
Higher number please

Guess the number: 75
Lower number please

Guess the number: 63
You have Guessed the number 63 correctly in 3 attempts
```

## Learning Objectives

This project helps beginners understand:

* Variables and data types
* Loops (`while`)
* Conditional statements (`if-elif`)
* User input handling
* Random number generation
* Basic game logic

## Author

**Abhiraj Sharma**
B.Tech (AI & ML) Student | Python Enthusiast
