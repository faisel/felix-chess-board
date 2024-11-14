# Felix's Chess Board

Welcome to Felix's Chess Board, a responsive, interactive chess game with an AI opponent. This project allows players to enjoy a game of chess against an AI with varying levels of difficulty, customize their board, and even undo moves if desired. The app is designed with a beautiful UI and responsive layout, making it enjoyable to use across devices.

## Features

- **Play Against AI**: Challenge yourself against an AI opponent with two difficulty levels: *Einfach* (Easy) and *Schwer* (Hard).
- **User Customization**: Choose your color (white or black) to play as and let the AI take the opposite side.
- **Responsive Board**: The chessboard resizes based on screen width, ensuring a great experience on both desktop and mobile.
- **Undo Last Move**: Made a mistake? Use the undo button to revert your last move.
- **Intelligent AI**: The AI in *Schwer* mode uses an advanced algorithm with Minimax and positional evaluation for a challenging experience.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/felix-chess-board.git
    cd felix-chess-board
    ```

2. **Include Dependencies**:
    - **jQuery** (for chessboard.js)
    - **chess.js** (for game logic)
    - **chessboard.js** (for board rendering)

    You can load these libraries from CDN as shown in the HTML code or download and serve them locally if desired.

3. **Run Locally**:
    Open `index.html` in your preferred browser to run the application.

## Usage

1. **Select Your Color**:
    - Choose either *Weiß* (White) or *Schwarz* (Black) from the dropdown to decide who makes the first move.

2. **Select Difficulty**:
    - Choose *Einfach* (Easy) for a casual experience.
    - Choose *Schwer* (Hard) for a more challenging game with the advanced AI algorithm.

3. **Play the Game**:
    - Drag and drop pieces to make your moves.
    - The AI will automatically respond after each user move.

4. **Undo Last Move**:
    - Click "Letzten Zug Rückgängig" to undo the last move for both you and the AI.

## Code Overview

- **HTML Structure**: `index.html` sets up the chessboard layout, styling, and player options.
- **CSS Styling**: Custom styles are added for responsive design, board colors, and UI elements.
- **JavaScript**:
    - **chess.js**: Handles game logic and rules.
    - **chessboard.js**: Manages the board display and piece movement.
    - **Minimax Algorithm**: The AI for *Schwer* difficulty uses Minimax with alpha-beta pruning, depth control, and positional evaluation for competitive play.

## Project Structure

