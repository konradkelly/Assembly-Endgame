# Assembly: Endgame

Assembly: Endgame is a word-guessing game built with React and Vite.
You must guess the hidden word before too many incorrect guesses eliminate the programming languages and Assembly takes over.

## Features

- Random word selection from a word bank for each game
- On-screen keyboard with correct and incorrect letter states
- Language "lives" system where each wrong guess removes one language
- Dynamic game status messages for win, loss, and wrong-guess farewells
- New Game button to reset and start a fresh round
- Accessibility support with aria-live status updates and screen-reader text

## Tech Stack

- React 19
- Vite 8
- clsx for conditional class names
- ESLint for linting

## Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Start the development server

```bash
npm run dev
```

### 3. Build for production

```bash
npm run build
```

### 4. Preview production build

```bash
npm run preview
```

### 5. Run lint checks

```bash
npm run lint
```

## How to Play

1. Click letters on the keyboard to guess the hidden word.
2. Correct guesses reveal matching letters.
3. Wrong guesses eliminate one language.
4. You win by revealing every letter before running out of languages.
5. If you lose, click New Game to start again with a new random word.

## Project Structure

```text
src/
	AssemblyEndgame.jsx   # Main game logic and UI
	App.css               # Game styles
	data/
		languages.js        # Language life definitions and colors
	utils.js              # Random word + farewell message helpers
	words.js              # Word bank
```
