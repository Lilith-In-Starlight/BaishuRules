# Rules Of Baishu
*Version: 0.2*

Baishu is a 2-player turn-based competitive strategy board game. It is played on a hexagonal grid with seven tiles on each side. Baishu is made to last long periods of time.

There are six elements: Fire, Order, Chaos, Air, Earth and Water. Usually, both players get 12 pieces of each element, however, this number may  be reduced or increased in order to make for shorter or longer games.

## During A Turn

1. One may place up to one piece. The only exception to this is the first turn, where one may place up to two pieces
2. One may do up to two movements. This means either moving a piece two spaces, or two pieces one space each. One can also swap the places of two pieces one owns, assuming they are adjacent.
3. Remove a piece. It is important that by the end of the turn one still has at least one piece on the board, as otherwise it'd count as surrendering. One can't place a piece that has been removed in the same turn.

## After A Turn

The following chart marks what elements extinguish other elements. For example, earth extinguishes fire.

![](https://i.imgur.com/pVxCxFi.png)



1. When a tile is surrounded by two or more tiles with elements that extinguish it, it is removed from the board and passed to the opponent. This is called capturing.
2. When a tile is surrounded by two or more tiles with elements that it extinguishes, it is removed from the board and becomes unplayable. This is called overwhelming.
3. If at any time a piece is subject to both of these rules, only the first one is applied.


## Win Conditions

1. A game ends when a player surrenders, either not putting any pieces in a board that doesn't have any piece of theirs, or by announcing surrender.
2. A game ends when the board is entirely occupied by a player, or the opponent is otherwise blocked from putting any pieces on the board.
3. A player loses when they have lost half their pieces of any element.


# Alternate Rulesets

## Baishuguoq

The only change occurs after a turn:

1. When a tile is surrounded by two or more tiles with elements that extinguish it, it is passed to the opponent **without being removed from the board**. This is called capturing.
2. When a tile is surrounded by two or more tiles with elements that it extinguishes, it is removed from the board and becomes unplayable. This is called overwhelming.

The third rule remains unchanged

## Baishu For Three Or More Players

It works exactly the same as the original Baishu, with the exception that captured pieces go to the person on your left. It supports up to six players.

# Changelog

**0.1**
The game was created after Athenaya joked about the 6-element system by saying "new rock paper scissors dropped"

**0.2**
+ A condition through which players can lose if they lose half their pieces of any element.
+ Tasha discovered that the way the elements interact is mechanically equivalent to having 3 elements. One of the inner triangles was inverted (specifically the earth one).
+ It was also discovered that it's possible for a piece to be both overwhelmed and captured. A rule has been added to say that it is captured.

**0.3**
+ Removed the rule where you lose if you lose all your pieces, since the one where you lose if you lose all your pieces of any element overrides it, and there's no way the former happens without the latter.
+ Added a rule to stop players from placing a piece that was removed in that same turn, as this impacts the late game.
+ Changed the default amount of pieces from 24 to 12.