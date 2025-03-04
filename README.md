# Tic Tac Toe - Assignment 4: Week 4

## Overview  
This is a simple Tic Tac Toe game built using HTML, CSS, and JavaScript. The game dynamically generates a 3x3 board and allows two players to take turns selecting squares. The starting player is randomly selected, and turns alternate between "X" and "O". The project is part of an assignment for learning DOM manipulation and event handling in JavaScript.  

## Link  
 

## Features  
- **Dynamic Board Generation**: The game board is created using JavaScript when the page loads.  
- **Random Starting Player**: Either "X" or "O" is randomly selected to start, and the first move corresponds to the correct starting player.  
- **Turn Tracking**: The current player's turn is displayed in a dedicated UI element and updates after each move.  
- **Click Event Handling**: Players can click on squares to place their mark, and the game prevents overwriting an already selected square.  
- **Win Condition Checking**: The game detects when a player has won or if there is a stalemate.  
- **Restart Button**: Clicking "Start Game" clears the board and re-randomizes the starting player.  
- **Basic UI Styling**: CSS is used to style the board, squares, and turn indicator.  

## Future Enhancements  
- **Improved UI/UX**: Adding animations and sound effects to enhance the user experience.  
- **Score Tracking**: Keeping track of wins, losses, and draws over multiple rounds.  

## How to Play  
1. Open `index.html` in a web browser.  
2. Click the **Start Game** button to randomly determine the starting player.  
3. Click on an empty square to place an "X" or "O" dependent on whose turn it currently is as seen in the UI.  
4. The turn alternates after each move, as indicated in the UI.  
5. The game announces a winner when three matching symbols align in a row, column, or diagonal.  
6. If all squares are filled without a winner, the game declares a **stalemate**.  
7. Click **Start Game** again to reset the board and start a new round.  

## Technologies Used  
- **HTML** - Provides the game structure.  
- **CSS** - Styles the board and UI elements.  
- **JavaScript** - Handles board generation, turn management, and win condition checking.  

## File Structure  
- `index.html` - Contains the main game structure and logic.  
- **Inline CSS** - Styles the game board, buttons, and text.  
- **Inline JavaScript** - Manages game logic, event handling, and UI updates.  

## Running the Project  
Simply open `index.html` in any modern web browser to play the game.  

## Author  
**Jessica Zolotarevsky**  
Email: [jez231@g.harvard.edu](mailto:jez231@g.harvard.edu)  
