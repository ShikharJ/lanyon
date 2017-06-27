---
layout: post
title: GSoC Progress - Week 4
---

Hello, this post contains the fourth report of my GSoC progress. Though I had planned on writing a new blog post every Monday, seems like I'm a bit late on that account.

## Report

### SymEngine
Last week I had mentioned that I'd be finishing up my work on `Range` set, however, after a talk with Isuru, it was decided to schedule it for the later part of the timeline. Instead I finished up on simplification of `Add` objects in `Sign` class through the PR [#1297](https://github.com/symengine/symengine/pull/1297).

Also, Isuru suggested implementing parser support for `Relationals`, which was required for `PyDy`. The work is currently in progress, through PR [#1298](https://github.com/symengine/symengine/pull/1298), after we hit an issue with dual-character operators (`<=` and `>=`), but we're working on it.

I sent in another PR [#1302](https://github.com/symengine/symengine/pull/1302) removing some redundant includes.

From now my work with `SymEngine` will probably be a little slower than usual, as I've started off wrapping classes in `SymEngine.py`, which is supposed to continue for some time from now.

### SymEngine.py
I pushed in [#162](https://github.com/symengine/symengine.py/pull/162) wrapping off a huge portion of the `functions` module in `SymEngine`. 

I'll be working on wrapping `Logic` classes and functions in the coming week, as well as finishing off my work on the parser support in `SymEngine`.

See you again!

**Vale**
