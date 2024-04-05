# Slot Machine Game

This is a simple slot machine game implemented in Python. In this game, players can place bets on multiple lines and spin the slot machine to potentially win prizes based on the combination of symbols they get.

## How to Play

1. **Deposit**: Players start by depositing money into their balance.
2. **Place Bet**: Players choose the number of lines to bet on and the amount to bet on each line.
3. **Spin**: Players spin the slot machine.
4. **Winning**: If the symbols on the slot machine align according to predefined winning patterns, players win prizes based on their bet.

## Game Rules

- Players can bet on up to 3 lines.
- The amount to bet on each line must be between $1 and $100.
- There are 4 symbols in the game: A, B, C, and D.
- Each symbol has a specific count and value associated with it.
- Winning combinations are determined by the alignment of symbols on the slot machine.
- Winnings are calculated based on the bet amount and the value of the symbols in the winning combination.

## Code Explanation

The game is implemented using Python and consists of the following components:

- **Constants**: Defines maximum lines, maximum bet, minimum bet, rows, and columns of the slot machine, as well as symbol counts and values.
- **Functions**:
  - `check_winnings`: Checks if the current spin results in any winnings.
  - `get_slot_machine_spin`: Generates a random spin of the slot machine.
  - `print_slot_machine`: Prints the current spin of the slot machine.
  - `deposit`: Allows the player to deposit money into their balance.
  - `get_number_of_lines`: Prompts the player to choose the number of lines to bet on.
  - `get_bet`: Prompts the player to choose the bet amount for each line.
  - `spin`: Executes a single spin of the slot machine.
  - `main`: Main function that orchestrates the game flow.

## How to Run

1. Ensure you have Python installed on your system.
2. Open a terminal or command prompt.
3. Navigate to the directory containing the Python script.
4. Run the script using the command `python3 main.py`.
5. Follow the on-screen instructions to play the game.

Have fun playing the slot machine game! If you encounter any issues or have suggestions for improvement, feel free to reach out to the developer.