# Connect-4

## Description
This project is a command-line version of the classic Connect-4 game. The game allows a player to play against an AI.

## Files
- **main.py**: The main script to run the game.
- **aiFunctions.py**: Contains the AI functionalities and logic.
- **boardFunctions.py**: Contains functions for handling and displaying the game board.
- **parameters.json**: Contains the game parameters such as the board size and symbols used.
- **requirements.txt**: Lists the required Python packages for the project.
- **fall.mp3, think.mp3, place.mp3**: Audio files used in the game.

## How to Run
1. Ensure you have Python installed.
2. Install the required packages using:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the game using:
   ```bash
   python3 main.py
   ```

## Game Rules
1. The game is played on a grid with 7 columns and 6 rows.
2. Players take turns dropping their symbol ('X' for the player, 'O' for the AI) from the top into one of the columns.
3. The first player to connect 4 of their symbols vertically, horizontally, or diagonally wins.

## Parameters
The parameters for the game can be adjusted in the `parameters.json` file. The current parameters are:
- `emptySpace`: The character representing an empty space on the board.
- `n_columns`: The number of columns in the game board.
- `n_rows`: The number of rows in the game board.

## Examples
An example of adjusting the parameters:
```json
{
    "emptySpace": ".",
    "n_columns": 10,
    "n_rows": 8
}
```
This will change the grid to 10 columns and 8 rows, and use '.' as the empty space character.

## Conclusion
Have fun playing and feel free to modify the parameters to customize your game experience!

## License
This project is licensed under the MIT License.
