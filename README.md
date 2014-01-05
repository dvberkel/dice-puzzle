Dice Puzzle
===========

This repository contains an exploration into an idea for a puzzle.

Puzzle
------

> Take eight ordinary dice. Stack them up to form a 2x2x2 cube such
> that all the 2x2 faces display the same number of pips.

Exploration
-----------

We use [magma][] to explore if a solution exist. To start a new
exploration remove both `progress.txt` and `solutions.txt` after
backing them up.

Then start a magma session and load `exploration.magma`. In the
session call the `run` procedure. An example run is depicted below.

```shell
load "exploration.magma";
run(10000);
```

One can monitor the progress by first touching `progress.txt` and
`solutions.txt` and tailing them.

[magma]: http://magma.maths.usyd.edu.au/magma/