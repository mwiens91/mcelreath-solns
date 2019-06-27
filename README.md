# mcelreath-solns

This repository contains a number of solutions to problems from the book
"Mathematical Models of Social Evolution: A Guide for the Perplexed"
(2007) by Richard McElreath and Robert Boyd.

## Errata

### Chapter 4 part 1

#### 4. Even bad guys are vulnerable

The payoffs V(ALLD|TF2T) and V(TF2T|ALLD) are wrong. Instead of being
2\*b and -2\*c, respectively, they should be b + w\*b and -c - w\*c,
respectively. The difference here is that the next iteration of the game
is not a given, and only happens with probability w. This change affects
the results in a mathematically meaningful sense, but in terms of
modelling, the conclusions drawn are the same.
