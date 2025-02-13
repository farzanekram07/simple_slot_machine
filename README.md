# Slot Machine Game

This is a simple command-line slot machine game written in Python. The game allows users to deposit money, place bets on multiple lines, and spin the slot machine to try and win money.

## Features
- Users can deposit money before playing.
- Choose the number of lines (1-3) to bet on.
- Place a bet amount within a predefined range.
- Randomly generated slot machine spins.
- Winnings are calculated based on matching symbols across chosen lines.
- The game continues until the user decides to quit.

## How to Run
1. Ensure you have Python installed on your system (Python 3.x recommended).
2. Download or clone this repository.
3. Open a terminal and navigate to the directory containing `slot_machine.py`.
4. Run the script using the command:
   ```bash
   python slot_machine.py
   ```
5. Follow the on-screen instructions to deposit money, place bets, and spin the slot machine.

## Game Rules
- The slot machine consists of a 3x3 grid.
- Symbols appear with different probabilities:
  - 'A' appears 2 times
  - 'B' appears 4 times
  - 'C' appears 6 times
  - 'D' appears 8 times
- Each symbol has a different value:
  - 'A' = 5x bet
  - 'B' = 4x bet
  - 'C' = 3x bet
  - 'D' = 2x bet
- A winning line must contain the same symbol in all three columns.
- Total winnings are calculated based on the bet amount multiplied by the symbol values.

## Example Gameplay
```
What would you like to deposit? $100
Enter the number of lines to bet on (1-3)? 2
What would you like to bet on each line? $10
You are betting $10 on 2 lines. Total bet is equal to: $20
A | B | C
B | B | B
C | C | C
You won $40.
You won on lines: 2
Current balance is $120
Press enter to play (q to quit).
```

## License
This project is licensed under the MIT License.

## Author
[SYED MOHAMMAD FARZAN EKRAM]

