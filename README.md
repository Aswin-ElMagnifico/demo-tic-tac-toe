# Tic-Tac-Toe Game

A classic Tic-Tac-Toe game built with React. Play against a friend and enjoy the timeless game with move history tracking.

## Features

- 🎮 Classic 3x3 Tic-Tac-Toe gameplay
- 🔄 Move history - jump back to any previous move
- ✅ Automatic winner detection
- 🎯 Turn indicator showing which player's turn it is
- 💻 Clean and responsive UI

## Technologies Used

- **React** 19.2.1
- **React DOM** 19.2.1
- **React Scripts** 5.0.0

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd demo-tic-tac-toe
```

2. Install dependencies:
```bash
npm install
```

### Running the Application

Start the development server:
```bash
npm start
```

The app will open in your browser at `http://localhost:3000`.

### Building for Production

Create an optimized production build:
```bash
npm run build
```

### Running Tests

Run the test suite:
```bash
npm test
```

## How to Play

1. The game starts with player X's turn
2. Click on any empty square to place your mark
3. Players alternate between X and O
4. The first player to get three marks in a row (horizontally, vertically, or diagonally) wins
5. Use the move history on the right to jump back to any previous move

## Project Structure

```
demo-tic-tac-toe/
├── public/
│   └── index.html          # HTML template
├── src/
│   ├── App.js              # Main game component with logic
│   ├── index.js            # React entry point
│   └── styles.css          # Game styles
├── package.json            # Dependencies and scripts
└── README.md               # This file
```

## Game Components

- **Square**: Individual clickable square component
- **Board**: 3x3 grid of squares with game logic
- **Game**: Main component managing game state and history

## License

This project is open source and available for educational purposes.
