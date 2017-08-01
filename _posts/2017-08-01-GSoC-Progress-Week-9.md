---
layout: post
title: GSoC Progress - Week 9
---

Hi all, we're in the final month of `GSoC` with only about 4 weeks remaining on the development time. Last week was a bit rough because my college semester started off with a heavy schedule on the very first day, and a number of boarding issues, due to which a number of my days were spent in shifting my stuff from one room to another. Add to that the summer heat of this country, and it becomes a total nightmare. Here's what I could do.

## Report

### SymEngine
I pushed in [#1316](https://github.com/symengine/symengine.py/pull/1316), resolving some of the scope issues we were facing in `SymEngine.py`. I'm expecting a light implementation schedule here in `SymEngine` form now on, as we have most of the stuff we need for a sizeable amount of `SymPy`'s directories to be ported over `SymEngine`.

### SymPy
Pushed in [#13051](https://github.com/sympy/sympy/pull/13051), fixing a minor piece of code that was previously preventing us from using `SymEngine`'s `igcd` in `SymPy`'s `LieAlgebras` module. I had also taken some time updating the work on other directories. 

### SymEngine.py
I worked on implementing some miscellaneous missing functionalities in [#179](https://github.com/symengine/symengine.py/pull/179), which should soon be ready to get merged.

Since we are slowly reaching towards the end of the project, I'll have to request Isuru for a release in `SymEngine` and `SymEngine.py` so that our latest work becomes available for `SymPy`.

**Pozdrav**
