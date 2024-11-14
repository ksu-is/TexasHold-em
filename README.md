The Poker Game Project is a text-based implementation of a Texas Hold'em poker game built in Python. The game allows players to simulate a poker game through a command-line interface, where they can compete against AI or other human players, participate in betting rounds, and try to form the best hand using a combination of their hole cards and community cards.

The main objective of the game is to allow players to experience the strategy, excitement, and challenge of playing Texas Hold'em poker in a simple, interactive, and engaging way. The project will focus on developing core game mechanics such as card dealing, hand evaluation, betting rounds, and managing player chips, while providing a clean, straightforward interface for users to interact with.

Deck of Cards:
A standard 52-card deck will be used.
Cards will be shuffled before each game to ensure randomness.
The deck will be used for both players' hole cards and community cards.

Player Setup:
Human players interact with the game via the command-line interface.
AI players will be controlled by simple decision-making algorithms.
Each player starts with a set number of chips.

Card Dealing:
Two hole cards are dealt to each player (face-down).
Community cards will be revealed in stages: the flop (3 cards), turn (1 card), and river (1 card).

Betting Rounds:
Betting will occur after each stage of card dealing (pre-flop, post-flop, post-turn, and post-river).
Players can bet, call, raise, or fold during each betting round.
The game will simulate betting logic, with each player making decisions based on their hand strength and the game state.

Hand Evaluation:
After the final betting round, players’ hands are evaluated according to standard poker hand rankings (e.g., pair, straight, flush, full house, etc.).
The player with the best hand wins the pot.

Pot Management:
The pot will accumulate chips during each betting round, and the winner takes all chips in the pot.
Players who fold will lose their chips for that round, and their contributions to the pot will be discarded.

Game Flow:
The game proceeds through multiple rounds:
Pre-flop: Players are dealt two hole cards, and the first betting round occurs.
Flop: Three community cards are revealed, followed by another betting round.
Turn: A fourth community card is revealed, and another betting round follows.
River: The fifth and final community card is revealed, and a final betting round occurs.
Showdown: If multiple players are still in the game after the final betting round, their hands are revealed, and the best hand wins

A good reference for a Python-based poker game is the repository python-poker. This repository provides a solid starting point for implementing a poker game in Python and includes logic for deck shuffling, dealing cards, and hand evaluation.
