---
layout: post
title: GSoC Progress - Week 2
---

Hello, this post contains the second report of my GSoC progress.

## Report

### SymEngine
This week I mostly worked on implementing specific classes in `SymEngine`, namely `Sign`, `Float` and `Ceiling`, through PRs [#1287](https://github.com/symengine/symengine/pull/1287) and [#1290](https://github.com/symengine/symengine/pull/1290). The work is currently under review, but again, mostly complete.

Though I had originally planned to implement more classes in my proposal, after a thorough look, I realised that a number of the mentioned classes could easily be implemented in `SymEngine.py` side only. As such, there was no hard requirement for them to be implemented in `SymEngine`.
Also, a number of them had been pre-implemented, but rather as `virtual` methods, and not standalone classes. There are still a couple of classes that I'd be working on in the coming week, which would effectively finish up a huge part of the planned Phase I of my proposal.

### SymEngine.py
Isuru and I conversed a bit on whether I'd be interested in working on providing `SymEngine` support for [PyDy](https://github.com/pydy/pydy) (a multi-body dynamics toolkit), as a part of GSoC. I agreed happily, and Isuru opened a couple of issues in `SymEngine.py` for me to work on, as I was completely new to `PyDy`.
I started off wrapping up `Infinity`, `NegInfinity`, `ComplexInfinity` and `NaN` classes through PR [#151](https://github.com/symengine/symengine.py/pull/151). I also worked on finishing Isuru's code, wrapping `ccode` and `CodePrinter` class with an improvised `doprint` function through PR [#152](https://github.com/symengine/symengine.py/pull/152).
I also opened [#153](https://github.com/symengine/symengine.py/pull/153), working on acquisition and release of `Global Interpreter Lock` or `GIL` in `pywrapper.cpp` file.

See you again!

**Au Revoir**
