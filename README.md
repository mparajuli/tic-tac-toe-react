# React Tic-Tac-Toe

A simple Tic-Tac-Toe game built using React. This project demonstrates the fundamentals of React components, state management, and event handling.

## Table of Contents

- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Game Features](#game-features)
- [How to Play](#how-to-play)
- [Contributing](#contributing)

## Getting Started

To run the Tic-Tac-Toe game locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/mparajuli/tic-tac-toe-react.git
```

2. Change into the project directory:

```bash
cd tic-tac-toe-react
```

3. Install dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm start
```

The game will be accessible at [http://localhost:3000](http://localhost:3000) in your web browser.

## Project Structure

- `index.css`: Styling for the game board and squares.
- `index.js`: Main entry point for the React application, containing the `Square`, `Board`, and `Game` components.
- `calculateWinner` function: Utility function to determine the winner of the game.
- `public/`: Static assets and the HTML file.
- `src/`: Source code for the React components.

## Game Features

- Classic 3x3 Tic-Tac-Toe board.
- Highlights winning squares when a player wins.
- Keeps track of game history and allows players to jump to previous moves.
- Indicates the winner or a draw when the game is over.

## How to Play

1. Click on an empty square to make a move.
2. The game alternates between "X" and "O" players.
3. The game ends when a player wins by completing a row, column, or diagonal, or when all squares are filled, resulting in a draw.

## Contributing

If you'd like to contribute to the project, please follow the standard GitHub workflow:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Submit a pull request.
