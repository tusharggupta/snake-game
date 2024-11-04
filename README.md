# snake-game
A simple C++ Snake Game for macOS, playable in the terminal. Use `W`, `A`, `S`, `D` keys to control the snake's movement, aiming to eat fruit (F) to grow. Game includes real-time updates and boundary collisions. Use `X` to exit the game.
This C++ Snake Game is a console-based implementation designed for macOS, playable in the terminal. The game allows users to control a snake using the `W`, `A`, `S`, `D` keys for movement, navigating a grid to eat randomly appearing fruit (denoted as `F`). Each time the snake consumes a fruit, it grows in length, making the game progressively more challenging as players must avoid colliding with the snake’s own body or the grid’s boundaries.

The code utilizes standard libraries for game mechanics and real-time user input. Since macOS doesn’t support `conio.h` (used for non-blocking input), this version leverages termios-based logic to achieve the same effect. This enables real-time snake movement updates without waiting for the player’s keypress, providing a smoother gameplay experience.

To run the game on macOS, use the command:
```bash
clang++ -std=c++14 snake.cpp -o snake
./snake
```

With each round, the player can continue to grow the snake by consuming fruit or press `X` to exit the game. This project demonstrates core programming skills in handling game logic, real-time input, and rendering within a text interface.
