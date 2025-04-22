# Tic Tac Toe Game

A modern implementation of the classic Tic Tac Toe game built with React. This project demonstrates component-based architecture and state management in React.

## Features

- Clean and modern UI
- Alternating X and O players
- Win detection
- Draw detection
- Game reset functionality
- Responsive design
- Hover effects and animations

## Project Structure

```
src/
├── componets/
│   ├── Square.jsx      # Individual square component
│   ├── board.jsx       # Game board component
│   ├── TicTacToe.js    # Main game component
│   └── TicTacToe.css   # Game styles
├── App.js              # Root component
├── App.css             # Global styles
├── index.js            # Application entry point
└── index.css           # Global styles
```

## Component Breakdown

- **Square**: Renders individual game squares and handles click events
- **Board**: Manages the 3x3 grid layout and square components
- **TicTacToe**: Contains game logic, state management, and win/draw detection

## Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd tic-tac-toe
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The game will open in your default browser at `http://localhost:3000`.

## How to Play

1. The game starts with player X
2. Click on any empty square to place your mark (X or O)
3. The game will automatically detect wins or draws
4. Use the "Reset Game" button to start a new game at any time

## Technologies Used

- React
- CSS3
- JavaScript (ES6+)

## Development

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App

## License

This project is open source and available under the [MIT License](LICENSE).
