Vires In Numeris ![Revision](https://img.shields.io/badge/rev-1.5-blue.svg)
================

[![Preview](https://img.shields.io/badge/PREVIEW-cards.md-green.svg)](game.md)

> Race for the longest Chain!

Spend HashRates to mine Blocks.
Mining rewards you with Coins.
Spend them on powerful Actions or collect them.
Play Actions card to favor yourself or attack your opponent(s).
The longest Chain ends the game.
The player with the most Blocks and Coins wins.

Components
----------

- Cards
  - HashRates (black) / Coins (orange)
  - Events (white): play right away
  - Actions (grey): play on your turn
    - Some are paid
    - Some can be played anytime

- Garbage: used Actions (visible)
- Deck: cards to draw (invisible)
- Pool: used HashRates (HR-face)
- Chain: your Blocks (B-face)
- Bank: your Coins (B-face)
- Hand: your cards yet to play (private)

Flow
----

Each player starts with a Genesis Block and a base reward.
Each turn, you draw cards: HashRates, Events or Actions.
Play those cards to favor yourself or attack your opponent(s).
With enough HashRates, you can mine a Block.
Blocks cost increasingly more HashRates to mine but always rewards a single Coin.
The longest Chain of Blocks will end the game.
The player with the most Blocks and Coins wins.

Setup
-----

- Duel — 50 HashRates (all but 14)
- 3 players — 56 HashRates (all but 8)
- 4-6 players — 64 HashRates (all)

Each player start with its own (free) Genesis Block and reward (1 Coin).
The Pool starts with nPlayers HashRates while players start with nothing in Hand.
When the Deck empties, reset the Pool (with nPlayers HashRates) and shuffle the rest with Garbage to make a new Deck.

You will need a binary source of randomness: a coin to flip usually works.

Rules
-----

You cannot loose your Genesis Block ever; nor your first Coin on first turn.
Banks store Coins, Pool stores HashRates (swap if necessary) and you Hand cannot store Events nor Coins.
Play clockwise. Start your turn by drawing 2 cards (+1 if your Hand was empty) from the Deck.
Play Events immediately. You can play any amount of cards but only gain 1 Block per turn. You are allowed to dismiss cards at the end of your turn.
When loosing Coins or HashRates, drop them in the Pool. Pay Coins from your Bank. Always pay HashRates from your Hand first, otherwise you are forced to swap Coins from your Bank for HashRates.

If a target cannot pay, the Pool always tries to compensate (clockwise, starting with the player that played the last card) until dry.
Mine a Block using the required amount of HashRates: 1st costs 1, 2nd costs 2...
When mined, keep 1 Coin as a Block of your Chain, get 1 Coin as a reward to your Bank and drop the rest in the Pool. Loosing a Block also makes you loose its reward.
The game ends when the required Chain length is reached. The player with the most Blocks and Coins wins (if tie, the longest Chain wins):
- Duel — 10 blocks
- 3 / 4 / 5 / 6 players — 8 / 7 / 6 / 5

Special cases
-------------

- You cannot swap at will. You cannot play an paid Action card you cannot afford.
- When exchanging, target must swap if necessary; otherwise, the Pool pays.
- When challenged, target must swap if necessary; otherwise the challenge is lost and the Pool pays.
- When stealing, target must swap if necessary; otherwise nothing gets stolen.
- "Strong"/"Weak" cards: can also apply to an opponent.
- "Test" card: cancels the last played card only, that returns to its original Hand and cannot be played again this turn from the same player.
- Event cards: the challengee is the player drawing the card.

CheatSheet
----------

Pool starts with nPlayers HashRates.
Draw 2 cards (+1 if Hand empty).
Play Events immediately.
Swap B for HR if required (not at will).
Pool tries to pay for broke players.
Challengee executes.
Anythin not paid to another player goes to the Pool as HashRate (swap if necessary).

- 2 players: 50 HashRates / 10 Blocks
- 3 players: 56 HashRates / 8 Blocks
- 4 players: 64 HashRates / 7 Blocks
- 5 players: 64 HashRates / 6 Blocks
- 6 players: 64 HashRates / 5 Blocks

Adjust HashRates to adapt difficulty (more HashRates is easier).
Adjust Blocks to adapt playing time (less Blocks is faster).

Credits
-------

- Concept
  - ShkSchneider(.github.io)
- Design
  - ShkSchneider
  - cryptoicons.co
  - Conthrax: Typodermic Fonts 
  - Exodar: Rometheme Studio
- Testing
  - ShkSchneider
  - MeJe

[![CC-BY-NC_SA](https://licensebuttons.net/l/by-nc-sa/3.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0)
