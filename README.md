# Abdul's Blackjack 🃏

This is a simple, browser-based implementation of Blackjack built using HTML, CSS, and JavaScript. The game allows a single player to draw cards, try to hit 21, and get feedback on their current status.

## Features

- 🎲 Random card generation simulating a deck
- 🧠 Basic Blackjack logic:
  - Aces count as 11
  - Face cards count as 10
- 🖼 Stylish background with golden theme
- 👤 Player object with name and chips display
- 🔄 Game state updates after each action

## Technologies Used

- HTML
- CSS
- Vanilla JavaScript

## How to Play

1. Click **START GAME** to begin a new round.
2. Two cards will be dealt, and the sum will be shown.
3. Click **NEW CARD** to draw additional cards.
4. Game ends when:
   - Your sum exceeds 21 (you lose),
   - You hit exactly 21 (Blackjack! 🎉),
   - Or you choose to stop drawing cards.

## File Structure

### `index.html`

Defines the UI:
- Title and game messages
- Card and sum display
- Buttons for game control
- Player info display

### `index.css`

Provides styling:
- Casino-themed background (`table.png`)
- Centered, bold UI with golden buttons
- Rounded buttons and responsive text

### `index.js`

Contains game logic:
- Handles card drawing and summing
- Manages game state: alive, Blackjack, busted
- Updates DOM elements dynamically
- Uses a `player` object to track name and chips

