# Introduction

Anyone on social media has no doubt seen posts that starts with "Wordle"
followed by some numbers then a bunch of colored blocks.  Apparently, this is
some new form of
[social currency](https://en.wikipedia.org/wiki/Social_currency).

As I understand it, there is a game in which people guess words, similar to
[Mastermind](https://en.wikipedia.org/wiki/Mastermind_(board_game)), but with
words.
While this is somewhat interesting, and I could have tried to build a tool
to help play the game, and throw around terms like [Levenshtein
distance](https://en.wikipedia.org/wiki/Levenshtein_distance), [longest common subsequence](https://en.wikipedia.org/wiki/Longest_common_subsequence_problem), [information gain](https://en.wikipedia.org/wiki/Information_gain_in_decision_trees), [constraint satisfaction](https://en.wikipedia.org/wiki/Constraint_satisfaction), [graph search](https://en.wikipedia.org/wiki/Graph_traversal), etc.
I would rather not.
As it turns out, what's being posted is just a simple string that
can be easily be constructed.
So I figured I'd just skip learning how to optimize playing the game
and just make a simple tool that constructs perfect score strings.

# Instructions

Go to the [score generator]() and enter the day identifier, the word length,
and maximim tries allowed.  Optionally you can check the hard mode box to get
the special '\*'.

You can then copy and paste the computed score string into a social media
post to impress all of your friends.

