---
layout: post
title: GSoC Progress - Week 8
---

My first two months under `GSoC` have finally ended, and we are right on track towards the completion of the project. I finished up on my log of `SymPy`'s directories and have analysed everything that needs to be further implemented or improved upon.

## Report

### SymEngine
I pushed in [#1313](https://github.com/symengine/symengine.py/pull/1313), implementing `row_insert` and `column_insert` functions in `DenseMatrix` class and `row_del` and `col_del` functions in `C` wrappers, while making `row_join`, `col_join`, `row_del` and `col_del` in-place member functions.

### SymPy
After testing all the viable directories that could use `SymEngine` as a backend, only the `LieAlgebras` module worked completely out of the box, with no major issues. As such, we were able to achieve the same through [#13023](https://github.com/sympy/sympy/pull/13023), which now marks the beginning of Phase III of my proposal. I have also pushed the work done on other directories as separate branches on my local repository, to be finished upon gradually.

### SymEngine.py
I worked on implementing the `Singleton` pattern in the wrappers through [#178](https://github.com/symengine/symengine.py/pull/178), though the work is currently in progress. More on this next week.

That's all I have for now.

**Bidāẏa**
