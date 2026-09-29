# Battleship

Classic Battleship against a bot. Place your five ships, then take turns
firing until one fleet is sunk.

Play it: https://milosarcade.com/battleship/

## How to play

1. Click your board to place each ship. Press R, or the Rotate button, to turn it.
   "Random fleet" places them all for you.
2. Press "Start battle".
3. Click a square in enemy waters to fire.

## Bot difficulty

| Level | How it plays |
|---|---|
| Easy | Fires at random and never follows up a hit |
| Normal | Usually tries next to a hit, but doesn't work out which way the ship lies |
| Hard | Follows the line of a ship once it has two hits |
| Expert | Hard, plus it skips squares too small to hide your smallest ship |

## Files

- `index.html` is the whole game: HTML, CSS and JavaScript in one file.
