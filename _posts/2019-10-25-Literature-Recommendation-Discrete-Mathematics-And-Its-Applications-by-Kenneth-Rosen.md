---
layout:	post
title: Literature Recommendation - Discrete Mathematics And Its Applications by Kenneth H. Rosen
---

<img align = "middle" src = "/assets/DMAIAKR.png">

While this book does not serve as a hard-core machine learning resource, I have to confess that I'm yet to come across another book that has helped me better in building a pre-requisite background for higher level mathematics, proof writing techniques and tricks which are heavily used in core computer science. Most undergraduate level courses on discrete mathematics rarely cover the entire material given in the book, given the breadth of the topics covered. So ideally, while you might feel that you would be missing out on crucial information by skipping a few chapters in between, I can assure you that the individual chapters in this book are pretty self-contained as well.

## The Writing Style
Much like Gilbert Strang's `Introduction to Linear Algebra`, this book introduces a rather intuitional approach to teaching the subject, leaving out proofs for the majority of the book. For people who are just entering college, this is an ideal resource for building a good math background for tackling undergraduate level CS courses. Since this book is mostly geared towards teaching the subject from a CS perspective, if you are more mathematically inclined, you might wish to explore other books that deal with the subject with a bit more mathematical rigour like `Concrete Mathematics: A Foundation for Computer Science` by Ronald Graham, Donald Knuth and Oren Patashnik or `Combinatorial Problems and Exercises` by László Lovász. For seasoned CS graduates, a vast majority of this book might fail to offer a reasonable amount of intellectual stimulation.

The highlighted theorems and lemmas are the most important feature of the book, especially for the situations where you might be inclined to use it as a quick reference. In addition to this, there are ample number of practice problems per chapter, of varying level of difficulty, to help in grasping the concepts better.

## Important Sections

### Chapter 1

The first chapter gently introduces propositional logic and rules of inference. While it may seem a bit redundant from the point of machine learning, I can safely guarantee that logic, and especially propositional logic, occupies a position of much importance, since most of the classical symbolic AI of the previous years heavily utilized propositional logic statements in order to derive further inferences from data. More recently, languages like `Prolog` make use of a similar paradigm, requiring regular English sentences to be translated into propositional statements. Equally important are the rules of inference, which help in simplifying these propositional statements and deriving meaningful results. Finally the chapter wraps up with the introduction to various proving methods and strategies that are later used throughout the book. If proof based mathematics wasn't a part of your regular high school experience, this portion of the book is a must read.

### Chapter 2

Next, we take a dive into naive set theory, and the introduction to functions, sequences and summations through sets. Most of the inference engines of the 1970s and later have made some or the other use of set theory. While many were based on naive set theoretic formulations, many simply transitioned to fuzzy sets and fuzzy logic theory pretty early on. While modern developments in the area, such as axiomatic set theory (of which most popular being `Zermelo-Fraenkel` set theory or `ZFC`) or fuzzy set theory, are not presented, the chapter does a great job in introducing some of the major developments of the field such as `Cantor diagonalization`, `Hilbert Hotel enumeration`, and countable and uncountable sets. The chapter ends with a formulation of the `Continuum Hypothesis` as stated by Georg Cantor.

### Chapters 3-4

The next two chapters focus on algorithmic growth and complexity, and number theory with applications to cryptography respectively. While these chapters can be given a quick read, I personally feel that there are better resources available for these sections, such as `Introduction to Algorithms` by Thomas Cormen, Charles Leiserson, Ronald Rivest and Clifford Stein (also known as `CLRS`)  and `Elementary Number Theory` by David Burton respectively, which contain a lot more information and are presented in a lucid manner as well.

### Chapter 5

Mathematical Induction is one of the most heavily used techniques when it comes to college level proof writing, and one should not take it lightly at any cost. While many have whined over time about the dullness of proofs that make use of induction, it nevertheless remains a strong method of theorem-proving. As such, the author has very rightfully dedicated an entire chapter to weak induction, strong induction, structural induction, and laid emphasis on its use in terms of recursive definitions and program correctness.

### Chapters 6-7

If you have prior experience with competition style mathematics, I highly doubt that the next two chapters would be of much difficulty to you. The sixth chapter only offers a concise introductory level view of combinatorics, which is quite easily covered in most high schools around the world. While certain portions of the text might be new to you, such as the generalized `Pigeonhole Principle` or `Ramsey Theory`, anything else should be a comfortable walk in the park. Similarly, the seventh chapter only offers a basic introduction to dicrete probability theory, with most of the emphasis being laid on `Bernoulli` and `Binomial` trials, and the use of `Bayes' Theorem`. While random variables, linearity of expectation and `Chebyshev's Inequality` are some of the new concepts which are presented, for a better set of problems and theory related to both combinatorics and discrete probability theory, I highly recommend `The Art of Problem Solving Volume 2: and Beyond` by Richard Rusczyk and Sandor Lehoczky.

### Chapter 8

Like the previous two chapters, this section is better learnt through a more focussed text as mentioned above. However, the chapter's coverage on solving linear recurrence relations is absolute gold, when it comes to clarity and completeness, and must be given a serious look. Recurrence relations occur heavily in real world problems, and more often than not, these relations tend to be linear in nature, and hence can be worked into closed form solutions.

### Chapter 9

This chapter succinctly introduces the notion of relations as a generalization of the concept of functions introduced in the second chapter. The concepts of reflexiveness, symmetricity and transitivity are also presented, along with the generalization to n-ary relations and their representations in terms of matrices. This is supplemented with the presentation of equivalence relations and partial orderings, which are heavily used in pretty much all of pure mathematics of the modern era, including `Real Analysis` and `Abstract Algebra`.

### Chapters 10-11

In my humble opinion, these two chapters are the most well exposited portions of the entire text. While there are other texts which provide a deeper insight into `Graph Theory`, I have personally found the book's treatment of this subject to be complete in terms of utility that an undergraduate might require. The terminologies, and representations introduced are completely self contained, and require no prior knowledge. `Isomorphisms`, `Connectivity`, `Euler and Hamiltonian Paths`, `Planar Graphs` and `Four Color Theorem` are some of the popular sections presented. Additionally, a reasonable treatment for trees as specialized graphs is also provided through traversal problems and spanning tree formulations. Mastering the material of these chapters are absolutely essential for a good insight into how and why many real-world problems are modelled on graphs and trees.

### Chapter 12

A refresher for boolean functions and logic gates, this chapter focuses heavily on the representation of boolean functions and the associated tricks for minimizing the logic circuits. I personally think this chapter can be given a quick overlook for its content.

### Chapter 13

While I encourage the reader to digest the material provided in the final chapter, it should come with a fair warning that most of the material covered here would be selectively handpicked from a formal course on `Formal Languages and Automata Theory`. As such, it is unfair to expect the same level of depth as one would expect from a dedicated book on the topic such as `Introduction to Automata Theory, Languages, and Computation` by John Hopcroft, Rajeev Motwani and Jeffrey Ullman, which I highly recommend.


In conclusion, I would like to say that if you are in a time-crunch, and wish to read this book in the fastest way possible, I'd recommend reading through the highlighted theorems and working your way through the starred **( * )** problems at the very least. Be cautious though, these are some pretty neat problems and might come off as too challenging to you, depending on your maturity in proof-based mathematics and problem solving. However, each of these is a must try problem, in order to master the material. Additionally, Prof. Tom Leighton's [MIT OCW course](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/) (from 2010) contains a lot of the material covered in the book, though the course follows an altogether different syllabus compared to the book.

**Do Androids Dream Of Eclectic Memes?**