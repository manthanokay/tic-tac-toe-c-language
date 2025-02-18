# Tic-Tac-Toe in C

## Description
This is a simple **Tic-Tac-Toe** game implemented in **C**, where a player competes against the computer. The player uses 'X', and the computer uses 'O'. The game runs in a console-based interface.

## Features
- Allows the player to make moves by entering row and column numbers.
- The computer makes random moves.
- Checks for a winner after every move.
- Displays the final game board and declares the winner or a tie.
- Option to restart the game after completion.

## How to Play
1. Run the program.
2. Enter the row and column numbers (1-3) when prompted.
3. The computer will then make its move.
4. The game continues until there is a winner or the board is full.
5. At the end, you can choose to play again by entering 'Y' or exit with 'N'.

## Compilation and Execution
### **Compile the program using GCC:**
```sh
gcc tic_tac_toe.c -o tic_tac_toe
```

### **Run the compiled program:**
```sh
./tic_tac_toe
```

## Code Overview
- **resetBoard()** → Initializes the board with empty spaces.
- **printBoard()** → Displays the current board state.
- **checkFreeSpaces()** → Returns the number of empty spaces left.
- **playerMove()** → Allows the player to input their move.
- **computerMove()** → Makes a random move for the computer.
- **checkWinner()** → Checks for a winning condition.
- **printWinner()** → Prints the result of the game.

