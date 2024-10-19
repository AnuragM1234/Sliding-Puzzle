# Sliding Puzzle Game

## Description

This is a web-based sliding puzzle game where players can enjoy the classic puzzle experience. The objective of the game is to slide the tiles around to rearrange them into a specific order.

## Features

- **Interactive User Interface**: A clean and responsive design for a smooth gaming experience.
- **Timer and Moves Counter**: Keep track of the time taken and the number of moves made.
- **Reset and Shuffle**: Options to restart the game or shuffle the tiles to start over.

## Technologies Used

- HTML
- CSS
- JavaScript

## Implementation

A* search algorithm is implemented and the heuristic used is Manhattan distance. [More info here. (https://en.wikipedia.org/wiki/A*_search_algorithm#:~:text=A*%20is%20an%20informed%20search,shortest%20time%2C%20etc.)

Used fast priority queue to increase the speed of solving.
The algorithm can only solve sized 2 and 3 grids quickly. Above that, it requires more time and demands space and processing power
