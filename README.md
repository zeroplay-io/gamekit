# GameKit

Lightweight mobile game development toolkit

## Introduction

GameKit is a React Native/Expo-based game development framework designed specifically for lightweight games like Sudoku, Poker, Match-3, and similar casual titles. It provides ready-to-use components and features so you can focus on your game logic.

## Quick Start

Create a new game project using templates:

```bash
npx @yourcompany/create-gamekit-app my-game --template puzzle
```

Or install the core package in your existing project:

```bash
npm install @yourcompany/gamekit-core
```

## Architecture

GameKit follows a modular design with three core packages: the core package provides essential capabilities like game state management, local storage, and timers; the UI package offers interface components such as game grids, buttons, modals, and theming system; the features package includes common game functionalities like check-in systems, leaderboards, and achievements.

We also provide four game templates: the puzzle template for games like Sudoku and sliding puzzles; the card template for Poker and UNO-style games; the casual template for Match-3 and 2048-style games; and the basic template that provides the simplest starting structure.
