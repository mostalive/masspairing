masspairing
===========
Exercise introduction and room layout for mass pairing exercise at
/dev/summer conference.

We organise a Mass Pair Programming Session at /dev/summer , because we
find that doing small katas is valuable and that programming together is
the best way to network for developers - what better way to get to know
another developer than develop together?. 

We have five rooms, [choose a room](languages-rooms.md) with the
language you want to. The mass pairing session takes place from 13:35 to
14:20 with a brief introduction in Room 1 at the start. Find someone you
have not met, or at least programmed with, before who also wants to
program in the same language. It's probably easiest if one of you has
previous experience in your language of choice, but you can be more
daring if you want. Katas are a great way to explore new languages.

Robert Chatley, Giovanni Asproni, Arnaud Bailly, Mark Dalgarno and
Willem van den Ende will be facilitating in each room, making sure you
have fun, and maybe learn something :).

## Why this exercies?
We chose the game of life, because if you practice it, you can do it in
a relatevily short amount of time. Emmanuel Gaillot ran it as a kata at
xp2005, afterwards it has been picked up as kata of choice for the
global day of code retreat. 

The goal of the exercise is not to rush to create a full solution, but
to work together in baby steps, working as well as you can. This
probably involves writing tests first, unless you use a dependently
typed language like Idris or Agda ;). We do recommend that you use
version control, commit ridiculously often, and just revert if you get stuck.

## Problem description
Taken from http://codingdojo.org/cgi-bin/index.pl?KataGameOfLife

Kata is about calculating the next generation of [Conway's game of
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

You should write a program that can accept an arbitrary grid of cells,
and will output a similar grid showing the next generation.

Clues

The input starting position could be a text file that looks like this:

Generation 1:

4 8

........

....*...

...**...

........

And the output could look like this:

Generation 2:

4 8

........

...**...

...**...

........

