Vires In Numeris
================

> Race for the longest Chain!

Spend HashRates to mine Blocks.

Mining rewards you with Coins.

Play Actions card to favor yourself or attack opponent(s).

The longest Chain ends the game.

The player with the most Blocks and Coins wins!

Abstract
--------

This card game has obvious inspirations from Bitcoin and its miners' race in the network.

Any prior knowledge is not required. Moreover, cards got information that might learn you a thing or two.

Each players act like a Node, competing to mine Blocks faster than the others using HashRates (computational power).

Blocks cost increasingly more HashRates to mine but always rewards a single Coin.

The longest Chain of Blocks will end the game. The player with the most Blocks and Coins wins.

Components
----------

- HashRates & Coins
- Events — to play right away
- Actions — play on your turn
  - some are paid (1 HashRate)
  - some can be played anytime

Genesis
-------

Each player start with its own (free) Genesis Block and reward (1 Coin). This Block cannot be lost.

The Pool starts with nPlayers HashRates while players start with nothing in Hand.

Setup the Deck by shuffling all HashRates, Actions and Events.

Have a source of randomness ready for challenges, usually as coin (the defied flips the coin).

Protocol
--------

Play clockwise. Start your turn by drawing 2 cards (+1 if your Hand was empty) from the Deck.

Play Events immediately. You can play any amount of cards but only mine 1 Block per turn. You are allowed to dismiss cards at the end of your turn.

Blocks cost increasingly more HashRates to mine but always rewards a single Coin:

Block #1 requires 1 HashRate.
Block #2 requires 2 HashRates.
And so on...

When you mine a Block:
- show all your required HashRates;
- flip one as a Block for your Chain (sideways);
- flip another as a Coin for your Bank;
- drop the rest in the Pool.

When loosing Coins or HashRates, drop them in the Pool. Pay Coins from your Bank. Always pay HashRates from your Hand first, otherwise you are forced to swap a Coin from your Bank for a HashRate.

If a player cannot pay you, the Pool always tries to compensate (clockwise, starting with the player that plays this turn) until dry.

When the Pool is empty, you must draw cards from the Deck until you get nPlayers HashRates for the Pool. Other cards are without effect.

When the Deck is empty at the end of your turn, you must fill the Pool with nPlayers HashRates and shuffle the rest with the Trash to make a new Deck.

At the end of your turn, you might suffer penalties (loose 1 HashRate):
- if you fail to refill the empty Pool;
- if you fail to refill the empty Deck;
- if you fail to get rid of the FIAT card.

The game ends when the required Chain length is reached. The player with the most Blocks and Coins wins (if tie, the longest Chain wins):
- 2 players — 10 Blocks
- 3 players — 8 Blocks
- 4 players — 7 Blocks
- 5 players — 6 Blocks
- 6 players — 5 Blocks

Adjust HashRates to adapt difficulty (more HashRates is easier).
Adjust Blocks to adapt playing time (less Blocks is faster).

Credits
-------

- Concept
  - ShkSchneider(.github.io)
- Design
  - ShkSchneider
  - CryptoIcons(.co)
  - Fonts: Conthrax, Raleway, Gayathri
- Texts
  - ShkSchneider
  - Alexandria: CoinMarketCap(.com)
- Testing
  - ShkSchneider
  - MeJe

Rev. 1.6 (2k21)

Licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0)

