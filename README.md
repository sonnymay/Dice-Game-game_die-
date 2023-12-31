# Dice Game :game_die:

Welcome to the Dice Game repository! This simple and fun game is developed in Python and simulates a dice-rolling game for 2 to 4 players. The goal is straightforward - the player who reaches the maximum score threshold first wins the game!

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have Python installed on your system. You can download and install Python [here](https://www.python.org/downloads/).

### Installing

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/sonnymay/DiceGame.git
   ```

2. Navigate to the directory where you cloned the repository.

3. Run the script:
   ```
   python dice_game.py
   ```

## How to Play

1. Start the game by running the script.
2. Enter the number of players: choose between 2 and 4 players.
3. The game starts with the first player. Each player gets a turn to roll the dice.
4. A player's turn continues until they decide to hold or roll a '1':
   - If the player rolls any number other than 1, they can choose to roll again to add to their turn total.
   - If they roll a 1, their turn is over, and they don't earn any points for that round.
   - If the player decides to hold, they save all the points they've earned during that turn.
5. The first player to reach or exceed the maximum score threshold (default is 50 points) wins the game.

## Game Rules

- The game is played with a regular six-sided die.
- Players take turns to roll the die.
- Each number rolled is added to the player's temporary score (turn total).
- If the player rolls a '1', their turn is over, and they lose all points accumulated in that turn.
- The player can choose to end their turn and "hold", which adds their turn total to their overall score.
- The game continues until a player's total score reaches or exceeds the set maximum score, at which point they are declared the winner.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

- **Sonny May** - *Initial work* - [SonnyMay](https://github.com/sonnymay)

See also the list of [contributors](https://github.com/sonnymay/DiceGame/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Hat tip to anyone whose code was used.
- Inspiration.
- etc.

---
