---
layout: post
title: Community Bonding - End Report
---

Greetings!

The Community Bonding period is officially closed and its time for the official coding period to begin. I had a great time reaching out to other fellow GSoCers in the community as well as conversing with my mentors over the project plans.

### The Tasks
Last week, I had mentioned that I'd be working on porting over `SymEngine` for `Parsing` and `Physics` modules. However, as pointed out by [Isuru](github.com/isuruf), there was no real gain in working on `Parsing`, as we already had a parser in `SymEngine`. Hence, my focus shifted on `Physics` and its sub-modules. As, such I've pushed in two PRs, covering `ContinuumMechanics`([#12660](https://github.com/sympy/sympy/pull/12660)) and `Hep`([#12655](https://github.com/sympy/sympy/pull/12655)) sub-modules to keep a track of the work. I've also been able to weed out most of the compatibility issues in the standalone files of `Physics` module. 

Though I had planned on finishing these tasks within the Community Bonding period itself, I realised that the `Quantum` and `Optics` sub-modules require a bit more work than what I had originally planned for the time. Nevertheless, I started off implementing `Relationals` in `SymEngine`, which was a task originally planned for the first week of the coding period. The PR([#1276](https://github.com/symengine/symengine/pull/1276)) is currently under review, and would be ready to merge within a day or two. The time gained thus will be devoted to the previously mentioned work, apart from what was originally planned in my proposal.

Besides, I also sent a PR([#1277](https://github.com/symengine/symengine/pull/1277)) fixing some minor grammatical errors which I stumbled upon in the codebase.

See you next week! Goodbye!
