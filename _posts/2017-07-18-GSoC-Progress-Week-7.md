---
layout: post
title: GSoC Progress - Week 7
---

My seventh report on my GSoC progress. It's been quite a journey so far, full of challenges and rewards. This week, apart from the work, I took some time to write a proposal for a full fledged talk at the upcoming `PyCon India 2017` Conference, titled `SymEngine: Leveraging The Power Of A Computer Algebra System (CAS) To Another` to be held during the first week of `November 2017` in `New Delhi`. What's more exciting is that Sumith and Ranjith would be there as well, hopefully if it gets selected.

## Report

### SymEngine
I pushed in [#1308](https://github.com/symengine/symengine.py/pull/1308) fixing a minor `Travis` irregularity.

### SymEngine.py
I pushed in [#176](https://github.com/symengine/symengine.py/pull/176), a minor PR for skipping some of the tests where `SymPy` wasn't being used.

Most of my time this week was spent on finding inconsistencies between `SymEngine` and `SymPy` objects which arise while using `SymEngine` in `SymPy`. I'm currently maitaining a log of all the issues that are occuring and their possible solutions. As such, I have decided to make a small change in our strategy. For the coming week, I'll try and complete the issue log, and implement the possible missing functionalities and attributes in `SymEngine.py`, after which a minor release in `SymEngine` and `SymEngine.py` would be made to make these changes available for `SymPy`.

Till Next Time!

**Ciao**
