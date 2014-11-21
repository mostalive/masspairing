Masspairing
===========
Exercise introduction for mass pairing exercise at
[fp days london](http://www.fpdays.net).

We organise a Mass Pair Programming Session at fp days, because we
find that doing that programming on an exercise together is
a great way to network and learn at the same time. 

We have seven tables, [choose a table](fpdays-tables.md) with the
language you want to. The mass pairing session takes place from 11:00 to
12:00. Find someone you have not met, or at least programmed with, before who also wants to
program in the same language. It's probably easiest if one of you has
previous experience in your language of choice, but you can be more
daring if you want. Small exercises are a great way to explore new languages.


## Problem description
Taken from
[codingdojo.org](http://codingdojo.org/cgi-bin/index.pl?KataGameOfLife).

Calculate the next generation of [Conway's game of
life](http://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) given any starting position.

You start with a two dimensional grid of cells, where each cell is
either alive or dead. In this version of the problem, the grid is
finite, and no life can exist off the edges. When calcuating the next
generation of the grid, follow these rules:

1. Any live cell with fewer than two live neighbours dies, as if
      caused by underpopulation.
2. Any live cell with more than three live neighbours dies, as if by
      overcrowding.
3. Any live cell with two or three live neighbours lives on to the
      next generation.
4. Any dead cell with exactly three live neighbours becomes a live
      cell.

If you finish this, try displaying the game (pretty graphics, or just a
console library) and running some iterations.

## Why this exercise?
We chose the game of life, because if you practice it, you can do it in
a relatively short amount of time. Once you go beyond a generation, and
do some display, the game has nice generative rules,
, a bit of state, some IO and a grid that could use a good representation. 

The goal of the exercise is not to rush to create a full solution, but
to work together in small steps, working as well as you can. This
might involve writing tests, unless you use a dependently
typed language like Idris or Agda ;). We do recommend that you use
version control, commit ridiculously often, and just revert if you get stuck.
