Masspairing
===========

https://www.github.com/mostalive/masspairing

TL;DR
-----

1. [Find a room that has your language of choice](languages-rooms)
2. Pair up with someone you have not worked with before, in a language that at least one of you has experience with.
3. Read exercise instructions at the bottom of this page
4. Set a timer to go off at 14:10
4. Code
4. Have Fun!
5. When the timer goes off, reflect with your peers in the room on how it went.

Long Intro
-----------
Exercise introduction and room layout for mass pairing
exercise at /dev/winter 2016

We find that doing small exercises is valuable for learning and that programming together is
the best way to network for developers - what better way to get to know
each other and have fun than write some code together.
About this Kata

Difficulty: easy

Good for teaching: does doing a SDUF (Small Design Up Front) taking monsters into account make a big difference in design and (initial and/or ongoing) velocity?

Related Katas: GameOfLife? - the board design was taken from there. We simulate a game you play continuously with turns.

First performed January 6 during a devnology.nl event at Marktplaats.nl. Kicked off by Marc Evers and Rob Westgeest, initial steps brainstormed and facilitated by Willem van den Ende, programmed by a majority of the participants :)

Problem Description

Pacman finds himself in a grid filled with monsters. Will he be able to eat all the dots on the board before the monsters eat him?

Incomplete list of things the game needs:

 * pacman is on a grid filled with dots
 * pacman has a direction
 * pacman moves on each tick
 * user can rotate pacman
 * pacman eats dots
 * pacman wraps around
 * pacman stops on wall
 * pacman will not rotate into a wall
 * game score (levels completed, number of dots eaten in this level)
 * monsters...
 * levels
 * animate pacman eating (mouth opens and closes)

Clues

You probably won't be able to complete all of the list in one night of dojo, however having the list (or starting with part of it and letting the participants brainstorm) makes for good design discussions. As in the game of life, a board representation does not have to be difficult. E.g. pacman starts in the centre of the board and is looking up (notice that pacman eats, so the V points downward because pacman has his mouth open):

. . .
.V.
. . .

Pacman looks continuous, however the game state changes in discrete steps. Creating a tick() method/function or somesuch, or passing a board to a function which returns a 'next state' board makes it easy to test the various conditions.

Suggested Test Cases

see the pacman project on github.com (mostalive/pacman) for actual steps from the first run.

Comments from those who are working on this Kata

Feel free to leave your comments here. I hope you enjoy this kata

# reflection
When the timer goes off reflect with the group. Consider the classes created. How many? How big? What mutable state? Consider the methods created How many? How long? Apply a few simple design metrics. How was the experience of working this way different from the usual? How could these ideas be applied in your day job?


