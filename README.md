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

## TDD as if you meant it

This is a favourite exercise, [devised by Keith Braithwaite](http://cumulative-hypotheses.org/2011/08/30/tdd-as-if-you-meant-it/) to take even smaller baby steps in programming. I have not dared test it with people who have not done TDD before, it might not be suitable, in that case you might decide to approach tic-tac-toe another way. For functional programmers, replace '_method_ with _function_ and _class_ with _module_ and _record_ in the instructions below..

We've modified Keiths' description a tiny bit to make it fit in the time. I recommend you read [his description, analysis and others' experiences](http://cumulative-hypotheses.org/2011/08/30/tdd-as-if-you-meant-it/) afterwards. The original suggests first to write tic-tac-toe how you would work normally, and then do it following the _TDD as if you meant it_ rules. We're going to dive straight in and do it with the _TDD as if you meant it_ rules:

1. Write exactly one new test, the smallest test you can that seems to point in the direction of a solution
2. See it fail
3. Make the test from (1) pass by writing the least implementation code you can in the test method.
4. Refactor to remove duplication, and otherwise as required to improve the design. Be strict about using these moves:
  1. *you want a new method—wait until refactoring time, then…* create new (non-test) methods by doing one of these, and in no other way:
    1. _preferred_: do Extract Method on implementation code created as per (3) to create a new method in the test class, or
    1. _if you must_: move implementation code as per (3) into an existing implementation method
  1. *you want a new class—wait until refactoring time, then…* create non-test classes to provide a destination for a Move Method and for no other reason
    1. populate implementation classes with methods by doing Move Method, and no other way

*The member of the pair without their hands on the keyboard must be very strict in enforcing these rules, especially 4.1 and 4.2*

In case you don't know, or forgot [rules for tic-tac-toe](https://en.wikipedia.org/wiki/Tic-tac-toe) also known as noughts and crosses.

When the timer goes off reflect with the group. Consider the classes created. How many? How big? What mutable state? Consider the methods created How many? How long? Apply a few simple design metrics. How was the experience of working this way different from the usual? How could these ideas be applied in your day job?


