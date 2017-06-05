---
layout: post
title: GSoC Progress - Week 1
---

Ahoy there! This post contains my first GSoC progress report.

## Report

### SymEngine
My previous PR([#1276](https://github.com/symengine/symengine/pull/1276)) on `Relationals` is reviewed and merged in. I also worked on introducing additional support for them. The PRs, [#1279](https://github.com/symengine/symengine/pull/1279) and [#1280](https://github.com/symengine/symengine/pull/1280) are also reviewed and merged, leaving only [LLVM support](https://github.com/symengine/symengine/pull/1282) as a work in progress.

I also noticed, that one of the pending requests for `0.3.0` milestone for `SymEngine.py` was the implementation of vector-specific methods such as `dot()` and `cross()` in `SymEngine`. The work is done [here](https://github.com/symengine/symengine/pull/1286) and is mostly complete.

Apart from this, I started the planned implementation of `SymPy` classes by implementing the `Dummy` class in `SymEngine` [here](https://github.com/symengine/symengine/pull/1284).

Most of the above mentioned pending work should be ready to merge within a couple of days.

### SymPy
Continuing my work on `sympy/physics`, I pushed in [#12703](https://github.com/sympy/sympy/pull/12703) covering the stand-alone files in `physics` module and [#12700](https://github.com/symengine/symengine/pull/12700) which is a minor addition to the work done in `physics/mechanics`.

### SymEngine.py
Isuru pointed out some inconsistencies in the existing code for `ImmutableMatrix` class, which needed to be fixed for `0.3.0` milestone. The code was fixed through the PR [#148](https://github.com/symengine/symengine.py/pull/148).


We'll probably have a `SymEngine.py` release next week, after which I plan to port over pre-existing functionalities in `SymEngine.py` to `SymPy`'s left-over modules.

That's all for now.

**Adiós**
