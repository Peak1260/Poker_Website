# Poker_Website

This is a simple poker game website built using ReactJS. It allows users to play a basic version of poker in the browser.

### Demo:
You can check out a live demo of the website here: [Poker Website](https://project-series-f21.web.app/)

### Betting System

- The game features a chip-based betting system. Each player starts with a set amount of chips.
- Players can place bets, and the system keeps track of their chip balances.
- The game enforces betting limits and ensures that players can only bet what they have in their chip stack.

### Player Actions

- Players can perform various actions during their turn, such as:
  - **Check:** A player can choose to check, which means they pass the turn to the next player without betting any chips.
  - **Call:** A player can match the current bet to stay in the game.
  - **Raise:** Players can raise the current bet, forcing others to match the new amount or fold.
  - **Fold:** A player can choose to fold, effectively exiting the current round.

### Winning Conditions

- The game determines the winner of each round based on hand rankings, including high card, pair, two pairs, etc.
- The player with the best hand wins the round and collects the chips from the pot.
