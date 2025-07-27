2048 game using C programming language.
=======================================


Console version of the game "2048" for GNU/Linux

##### Gameplay

You can move the tiles in four directions using the arrow keys: up, down, left, and right. All numbers on the board will slide into that direction until they hit the wall and if they bump into each other then two numbers will be combined into one if they have the same value. Each number will only be combined once per move. Every move a new number 2 or 4 appears. If you have a 2048 on the board you have won, but you lose once the board is full and you cannot make a move.

##### Requirements

- C compiler

Tested on: GNU/Linux, Parrot, Ubuntu

##### Installation

 Compile from source (recommended):

``
from 2048_game_vatsank
main.cc

eg:

cd Desktop  (location where the file is saved)
cd 2048_game_vatsank
g++ main.cc
./a.out

```

##### Running

The game supports different color schemes. This depends on ANSI support for 88 or 256 colors. If there are not enough colors supported the game will fallback to black and white (still very much playable).



All tests are executed successfully.
