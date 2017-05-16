---
layout: post
title: Community Bonding - Progress Report
---

Hello there!
It is the half-time in Community Bonding period, which will be officially closed in a couple of weeks. Since its been two weeks since I last posted, I thought it would be better to provide an update about the progress made.

### Community Bonding

I had a number of conversations with [Isuru](https://github.com/isuruf), a lot of which cornered around PR reviews and workarounds, and the plans for the next two weeks.

As a part of the community bonding, I'm becoming comfortable with `Cython` syntax and programming nuances by the day. Though I'm not completely thorough with the language, I think undertaking some amount of work would be the best way through.
Here is a gist of the work I undertook till now:

**Merged**

**SymEngine**

[#1269](https://github.com/symengine/symengine/pull/1269) Implemented additional functionalities for class `DenseMatrix`

**SymEngine.py**

[#140](https://github.com/symengine/symengine.py/pull/140) Implemented `Float` class and ported functions to `sympy/sympy_compat.py`

[#129](https://github.com/symengine/symengine.py/pull/129) Introduced `MutableDenseMatrix` and `ImmutableDenseMatrix` in `symengine_wrapper.pyx`

**Pending**

**SymEngine**

[#1267](https://github.com/symengine/symengine/pull/1267) Removing redundant `inline` declarations and moving implementations to `.cpp` files from the headers

[#1251](https://github.com/symengine/symengine/pull/1251) Applying `-Wsign-conversion` flag and fixing the warnings

**SymEngine.py**

[#128](https://github.com/symengine/symengine.py/pull/128) Making `Subs` and `Derivative` classes closer to their `SymPy` implementations

[#126](https://github.com/symengine/symengine.py/pull/126) Wrapping `Min` and `Max` functions from SymPy

`SymEngine.py` has a planned release (`0.3.0`) scheduled for the 29th of this month, right before the official coding period begins. Hence, I will most probably be working on the pending PRs in the coming days.

In my proposal, I had also planned on porting over `SymEngine` as a backend for simpler modules such as `Physics` and `Parsing`, which would be my main goal for now, and I'll continue with this till the Community Bonding period ends.

Catch you later!
