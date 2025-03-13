# Tic Tac Toe in C

## Overview
This is a simple console-based Tic Tac Toe game written in C. Two players take turns to mark the grid, and the game checks for a winner or a draw after every move.

## Features
- **Two-player mode**
- **Simple text-based UI**
- **Win/draw detection**

## How to Compile and Run
### Using GCC (Linux/Windows)
```bash
gcc tictactoe.c -o tictactoe
./tictactoe
```

### Using Turbo C++ (Windows)
1. Open the file in Turbo C++.
2. Compile and run the program.

## How to Play
1. Players take turns entering a number (1-9) corresponding to the grid position.
2. The game updates the board and checks for a winner.
3. If all spaces are filled without a winner, the game declares a draw.

## Game Board Layout
```
     |     |     
  1  |  2  |  3  
_____|_____|_____
     |     |     
  4  |  5  |  6  
_____|_____|_____
     |     |     
  7  |  8  |  9  
     |     |     
```

## Known Issues
- The `system("cls")` command is used for clearing the screen, which works on Windows but may need `system("clear")` for Linux.
- Invalid input handling could be improved.

## Contributions
Feel free to fork this repository, report issues, or submit pull requests.

## License
This project is licensed under the MIT License.

## Author
Developed by Harsh Arora

