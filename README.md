# Tic Tac Toe

A simple and interactive Tic Tac Toe game built with React.

## Overview

This project is a web-based implementation of the classic 3x3 Tic Tac Toe game for two players. Players take turns placing `X` and `O`, and the game detects the winner when three matching symbols align horizontally, vertically, or diagonally.

## Features

- Two-player gameplay (`X` and `O`)
- Winner detection logic
- Move history tracking
- Restart game button
- Clean and responsive UI

## Tech Stack

- React
- JavaScript (ES6+)
- CSS
- React Router

## Game Rules

1. The game is played on a 3x3 grid.
2. Player `X` goes first, then player `O`.
3. The first player to align 3 marks in a row wins.
4. If all 9 cells are filled without a winner, the game is a draw.

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm

### Installation

```bash
npm install
```

### Run Locally

```bash
npm start
```

Open `http://localhost:3000` in your browser.

## Available Scripts

- `npm start` - Starts the development server
- `npm run build` - Creates a production build
- `npm test` - Runs tests in watch mode
- `npm run deploy` - Deploys the build with `gh-pages`

## Deployment

This project includes `gh-pages` deployment scripts. Before deploying, update `homepage` in `package.json` to match your GitHub Pages URL:

`https://<your-username>.github.io/<repo-name>`

Then run:

```bash
npm run deploy
```

## License

This project is licensed under the terms in `LICENSE.md`.
