---
layout: post
title: GSoC Progress - Week 3
---

Hello, this post contains the third report of my GSoC progress. This week was mostly spent on learning the internal structures of `SymEngine` functionalities and methods on a deeper level.

## Report

### SymEngine
This week I worked on implementing `Conjugate` class and the related methods in `SymEngine`, through PR [#1295](https://github.com/symengine/symengine/pull/1295).

I also worked on implementing the "fancy-set" `Range`, the code for which would be complete enough to be pushed sometime in the coming GSoC week. 

Also, since it would probably be the last week that I'd be working on `SymEngine`, I spent some time going through the codebase and checking for discontinuities between `SymEngine` and `SymPy`'s implementations.

### SymEngine.py
I pushed in [#155](https://github.com/symengine/symengine.py/pull/155) fixing a trivial change from `_sympify` to `sympify` in relevant cases throughout the `SymEngine.py` codebase. The PR is reviewed and merged.

I reached out to Isuru once again regarding further work to be undertaken for `PyDy`, and he suggested wrapping up `Relationals` from `SymEngine`. The work, which is pushed through [#159](https://github.com/symengine/symengine.py/pull/159), is in itself close to completion, with only specific parsing capabilities left to be implemented (for eg.  `x < y` should return a `LessThan(x, y)` object). 

Wrapping `Relationals` also marks the initiation of `SymEngine.py`'s side of Phase II, which predominantly focuses on bug-fixing and wrapping.

See you again!

**Addio**
