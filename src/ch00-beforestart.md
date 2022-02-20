# Before Starting

## Prerequisites

Familiarity with fundamental mechanics of modern Tetris is expected. Knowledge of basic modular arithmetic is beneficial. Although appreciation of the theory requires only a logical mindset, mastery of the SRS rotation system is recommended for practical solving.

## Notation for piece queues

The notation described is consistent with that used by knewjade’s sfinder.

_“Tetrominos”_ (used interchangeably with _“pieces”_) are any of `T`, `I`, `L`, `J`, `S`, `Z`, and `O`.

Sets of tetrominos are denoted by a sequence of tetrominos enclosed by a pair of square brackets. Square brackets followed by `pN` where `N` is a natural number denotes drawing `N` pieces randomly from the set enclosed by the square brackets without replacement. Square brackets without the following `pN` is shorthand for `p1`.

An asterisk (\*) is shorthand for `[TILJSZO]`.

A valid piece queue is composed of single tetrominos and square bracket clauses that may be separated by commas (,) for clarity.

### Examples

1. `ILSZ` or equivalently `I,L,S,Z` specifies one distinct queue of four pieces.
1. `[ILSZ]p4` specifies 24 distinct queues of four pieces.
1. `T,*p7` specifies 5040 distinct queues of eight pieces.
