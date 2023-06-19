# Game of Life

This is a Python implementation of Conway's Game of Life using the Pygame library. The Game of Life is a cellular automaton that follows a set of simple rules and produces interesting patterns and behaviors.

## Installation

To run the Game of Life program, follow these steps:

1. Ensure you have Python 3.x installed on your system.
2. Install the necessary libraries by running the following commands in your terminal or command prompt:
   ```
   pip install pygame
   pip install numpy
   ```
3. Download the `game_of_life.py` file from the repository.
4. Open a terminal or command prompt and navigate to the directory where you saved `game_of_life.py`.

## Usage

To start the Game of Life simulation, run the following command:

```
python game_of_life.py
```
Or you can simply double click on the `game_of_life.py` file to run the program.

## Controls

- **Spacebar:** Start or stop the simulation.
- **Mouse Click:** Toggle the state of a cell (alive or dead).

## Rules of the Game

The Game of Life follows the following rules:

1. Any live cell with fewer than two live neighbors dies, as if by underpopulation.
2. Any live cell with two or three live neighbors lives on to the next generation.
3. Any live cell with more than three live neighbors dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

## Customization

You can customize certain aspects of the simulation by modifying the code in `game_of_life.py`. Here are some examples:

- Adjust the size of the cells by changing the `size` variable in the `main` function.
- Modify the dimensions of the grid by changing the values in the `cells` array initialization.
- Experiment with different colors by modifying the color values in the code.

## Contributing

Feel free to contribute to this project by submitting bug reports, feature requests, or pull requests on the repository page.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
