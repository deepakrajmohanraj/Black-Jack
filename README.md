# Blackjack Game

This is a simple implementation of a Blackjack game in Python. The game is played in the console, and you can specify the number of games you want to play.

## How to Play

1. Run the Python script `blackjack.py`.
2. Enter the number of games you want to play when prompted.
3. Follow the on-screen instructions to play the game.

## Gameplay

- The game uses a standard deck of cards.
- You (the player) are dealt two cards initially.
- The dealer is also dealt two cards, with one card hidden.
- You can choose to "Hit" (draw a card) or "Stand" (keep your current hand).
- The goal is to have a hand value as close to 21 as possible without exceeding it.
- The dealer will draw cards until their hand value is at least 17.
- The game checks for blackjack, busts, and determines the winner based on hand values.

## Classes

### `Game`

- The main class that orchestrates the game.
- Manages the overall game flow, including dealing cards and checking for winners.

### `Hand`

- Represents a player's or dealer's hand of cards.
- Calculates and displays the hand value.
- Handles aces to ensure optimal hand values.

### `Card`

- Represents an individual playing card.
- Displays the card's rank and suit.

### `Deck`

- Represents a deck of cards.
- Can be shuffled, and cards can be dealt from the deck.

## Usage

Feel free to use, modify, or enhance the code as you see fit. Contrib
