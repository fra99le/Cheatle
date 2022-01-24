# Introduction

Anyone on social media has no doubt seen posts that start with "Wordle"
followed by some numbers then a bunch of colored blocks.  Apparently, this is
some strange new form of [social currency](https://en.wikipedia.org/wiki/Social_currency).

As I understand things, it is a game similar to [Mastermind](https://en.wikipedia.org/wiki/Mastermind_(board_game)), in which people guess words.
While this is somewhat interesting, and I could have tried to build a tool
to help play the game, perhaps throwing around terms like [Levenshtein
distance](https://en.wikipedia.org/wiki/Levenshtein_distance), [longest common subsequence](https://en.wikipedia.org/wiki/Longest_common_subsequence_problem), [information gain](https://en.wikipedia.org/wiki/Information_gain_in_decision_trees), [constraint satisfaction](https://en.wikipedia.org/wiki/Constraint_satisfaction), [graph search](https://en.wikipedia.org/wiki/Graph_traversal), etc.,
I would rather not.

As it turns out, what's being posted is just a simple string that
can be easily be constructed.
So I figured I'd just skip learning how to play the game, let alone optimizing game play, and just make a simple tool that constructs perfect score strings.

# Instructions

Go to the [score generator](https://fra99le.github.io/Cheatle/) and enter the day identifier, the word length,
and maximim tries allowed.  Optionally you can check the hard mode box to get
the special '\*'.

You can then copy and paste the computed score string into a social media
post to impress all of your friends.

