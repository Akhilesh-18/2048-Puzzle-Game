
# 2048 Puzzle Game

In the puzzle game 2048, a single player must combine identical tiles to produce new ones with greater numbers. By continuously merging tiles with the same value, the game's objective is to produce a tile with the number 2048.

A grid of tiles that can be moved up, down, left, or right is controlled by the player in the game. All of the tiles on the board slide in the direction the player directs them when moving the tiles until they run into a barrier, such as another tile or the board's edge. When two moving tiles of the same value collide, they combine to form a single tile of the sum of the added values.

For example, if two tiles with the value "2" collide, they will merge into a single tile with the value "4". If two tiles with the value "4" collide, they will merge into a single tile with the value "8". The game ends when there are no more moves left on the board.


## Procedure

- Set up the HTML structure for the game board. This will typically involve creating a div element to contain the game tiles, and nested div elements for each tile.

- Write JavaScript code to generate new tiles at random positions on the game board. You can use a function that generates a random number between 0 and 3 to determine the position of the tile, and assign a value of 2 or 4 to the tile.

- Write a function to move the tiles on the board. This function should take into account the direction of movement (left, right, up, or down) and update the positions of the tiles accordingly.

- Write a function to merge tiles with the same value. This function should check for tiles with the same value that are adjacent to each other, and merge them into a single tile with a value that is the sum of the original tiles.

- Use JavaScript to listen for user input, such as arrow key presses or swipe gestures, and call the appropriate functions to update the game state and move the tiles on the board.

- Add a game loop to update the game state and redraw the game board at regular intervals.


## Demo Link

https://akhilesh-18.github.io/2048-Puzzle-Game/

NOTE:
Use Screen Fit size of 90 % for better User Experience  :‑P