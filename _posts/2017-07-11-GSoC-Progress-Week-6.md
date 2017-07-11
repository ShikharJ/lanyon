---
layout: post
title: GSoC Progress - Week 6
---

This week, quite like the previous week, my work was mostly limited to `SymEngine.py`.

## Report

### SymEngine.py
I pushed in [#172](https://github.com/symengine/symengine.py/pull/172) wrapping off some of the miscellaneous functions, and aliasing some of the existing ones to make them compatible with `SymPy`.

Since the above PR practically sums up my work in `SymEngine.py`, it's safe to say no new functionality is expected to be wrapped for now. However, since `sympy/physics/vector` and a number of other modules are currently failing with `SymEngine`, after the `0.3.0` release of `SymEngine.py`, some minor tweaks would be required in the wrappers. Also, I'll try and get all the pending PRs merged as soon as possible.

Till Next Time!

**Adéu**
