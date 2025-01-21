React Tic Tac Toe Game
Overview
This is a simple yet engaging Tic Tac Toe game built with React. The application allows two players to take turns, updates the game board dynamically, and announces the winner or a draw at the end of the game. It also features a log of all moves and the ability to restart the game.

Features
Two Player Mode: Players can customize their names and alternate turns.
Dynamic Game Board: Updates in real-time based on player moves.
Winner Detection: The game identifies the winner or a draw automatically.
Game Log: Displays a log of all moves made during the game.
Restart Functionality: Easily restart the game at any time.
Components
Player: Displays player information and allows name changes.
GameBoard: Renders the Tic Tac Toe board and handles square selection.
Log: Shows the sequence of moves made by the players.
GameOver: Announces the winner or a draw and provides a restart option.
Setup Instructions
Clone the Repository:

bash

git clone https://github.com/your-username/react-tic-tac-toe.git
Navigate to the Project Directory:

bash

cd react-tic-tac-toe
Install Dependencies:

bash

npm install
Start the Development Server:

bash

npm start

Open the Game: The game will be available at http://localhost:3000 in your browser.

How to Play
Enter Player Names: Customize the names of Player 1 (X) and Player 2 (O).
Take Turns: Click on the squares to make a move.
Win or Draw: The game announces the winner when three marks align or a draw if the board is full.
Restart: Click the restart button to play again.

Winning Combinations
The game checks for the following winning combinations:

Three in a row horizontally.
Three in a row vertically.
Three in a row diagonally.
Customization
You can easily customize the game by:

Modifying player names dynamically.
Adjusting the game logic in winning-combinations.js for custom win conditions.
Technologies Used
React: For building the user interface.
JavaScript: Core logic for game functionalities.
CSS: Basic styling for the components.
License
This project is open-source and available under the MIT License.

Contribution
Feel free to fork the repository and submit pull requests. Contributions, bug reports, and feature requests are welcome!

Enjoy playing and happy coding!