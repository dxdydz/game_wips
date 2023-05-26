# Domizone

A tile-laying and area control game for icehouse and dominoes, loosely inspired by Carcassonne.

## Equipment

- 1 monochrome trio per player
- 1 set of double six dominoes, large enough for a large pyramid to sit comfortably on top

## Setup

Give each player a trio in their color, these pieces will be played on dominoes to claim areas. Shuffle the dominoes and deal a hand of six dominoes to each player.

## Play

Take turns. On the very first turn, the first player will play a domino from their hand to the middle of the table. On all subsequent turns:

- You must play a domino from your hand to the table, if possible.
  - Dominos must have at least one part touching another domino such that the pip count on the two touching halves match. Dominos do not need to match the pip-count of every piece/half they are touching, but must match at least one.
  - Dominos are played to an imaginary 8x8 grid that is formed through play (cf, the 3x3 grid in Tic-Tac-Doh!). Each half of a domino is considered one unit of this grid (so a domino covers two spaces, and four dominos laid end-to-end would span the full extent of the grid -- no further dominoes could be played past either end).
  - If you are unable to make a valid domino placement, you must draw a domino. Your turn is over.
- You may place one of your three pyramids on half of the just-placed domino. This pyramid will claim the group of contiguous like-valued squares for scoring at the end of the game. 
  - Pyramids can not be placed on a group that already has another pyramid placed on it (eg, if you play a 2-6 domino next to a group of 6s, and your opponent already has a pyramid on one of the 6s, you can not place a pyramid on the 6). However, you can place a pyramid on a domino half and later link it up to an existing group that contains a pyramid (think farm battles in Carcassonne).
- Draw another domino to replace the one you played.

## End and Scoring

The game ends when neither player is able to play (there are no valid moves and no more dominos in the draw pile). Players score the areas they claimed.

For each group a player has a pyramid on, that player scores the size of the pyramid times the size of the group. For example, if Jorge had a medium pyramid on a group of 4 blanks (4 blank domino halves connected orthogonally), Jorge would score 2x4=8 points for that group. Two players may score the same group in the event that they both have a pyramid on that group, and a single player can score a group with more than one pyramid in a similar scenario, provided all pyramids were placed legally during play.

Whichever player has the most points, wins.
