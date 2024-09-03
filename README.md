# PRODIGY_WD_03

### README: Tic Tac Toe with Score

#### Project Overview
This project is a simple web-based Tic Tac Toe game with a scoreboard feature. The game is played between two players, "X" and "O", who take turns marking the spaces in a 3x3 grid. The game keeps track of the scores for each player, updating the score when a player wins. If the game ends in a draw, no points are awarded. Players can restart the game at any time without resetting the scores.

#### Files
- **index.html**: This is the main file that contains the HTML structure, styling, and JavaScript logic for the game.

#### Features
- **Interactive Grid**: Players can click on the squares of the grid to mark their move.
- **Scoreboard**: Displays the current score for both players "X" and "O".
- **Restart Game Button**: Allows players to reset the board and start a new game while retaining the current scores.

#### How to Use
1. **Load the Game**: Open the `index.html` file in a web browser.
2. **Play the Game**: Click on any square in the 3x3 grid to make your move. Players alternate between "X" and "O".
3. **Winning**: The game will automatically check for a winner after each move. If a player wins, an alert will notify them, and the scoreboard will update.
4. **Draw**: If all squares are filled and no player has won, the game will end in a draw, and an alert will notify the players.
5. **Restart the Game**: Click the "Restart Game" button to reset the board for a new game. Scores will be retained.

#### Code Explanation
- **HTML Structure**:
  - The page contains a title, a 3x3 grid of div elements for the game board, a scoreboard to display player scores, and a reset button.
  
- **CSS Styling**:
  - The grid is styled with Flexbox to center the game board. The squares have a uniform size and color scheme, with a grid layout.
  
- **JavaScript Logic**:
  - The game logic is handled in JavaScript. It keeps track of the board state, checks for winning combinations, and updates the scoreboard.
  - Event listeners are added to each square to handle player moves, and the reset button is used to clear the board for a new game.

##Deployment

link : 
