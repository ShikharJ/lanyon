---
layout:	post
title: Literature Recommendation - Introduction To Linear Algebra by Gilbert Strang
---

<img align = "center" src="/assets/ILAGS.png">

For those of you greenhorns that have just made your venture into the world of machine learning, it must not come as a surprise to you that linear algebra is the purest soul of the realm. Most of the ML and optimization world borrows ideas heavily from the same, and it is single-handedly the most important area of mathematics that will dictate your level of thinking while tackling ML problems.

As such, it is altogether fitting to write about a text that has probably helped thousands of undergraduates to get up and running with their knowledge of linear algebra. Prof. Gilbert Strang's book is one such epitome of awesome insights into the field. There are probably very books out there that are worth reading over and over again, Strang's book being one such gem. I have personally read this book many times over the course of my undergrad, and have always felt that I learnt something completely new each time. I would not be exaggerating if I said that you should keep this book in your personal collection of self-help books. Here are some of the points which I must mention, which make it such an important read.

## The Writing Style
Strang takes up a non-rigorous approach to teaching the subject. He mentions a concept dead straight, tells you why it is important and mentions how it relates to the bigger picture of algebraic and geometric meaning. Very few formal proofs are provided in the text, with the author emphasizing on the importance to derive the non-rigorous connections to other fields of mathematics. 

While many professionals would argue that this method of teaching is specifically aimed at non-mathematicians (since the flavour is rather numerical than theoretical), I personally think this is an amazing way to approach a deeply theoretical subject without having to raise the bar of abstraction to the level that is incomprehensible to most people. If you have read any standard book on abstract algebra, you would notice that linear algebra and vector fields are typically not even introduced in the first ten or so chapters. This leads to a huge jump in abstraction that most undergraduates would not be prepared to handle. That being said, one should first strive to master the concepts introduced in the text before moving on to a more theory oriented text. The book is entirely self-contained, and the recommended way to learning the material would be to rather forget the concepts of matrices and determinants that one learns during the typical high school system, and approach the book with a fresh mind.

## Important Sections

### Chapters 1-2

The first couple of chapters act as a refresher material for the concepts of vectors, coordinate geometry and matrix operations that a student typically learns during their high school, while introducing the concepts of `Gaussian` elimination techniques for solving systems of equations. Extremely insightful and important, especially from a standpoint of numerical linear algebra.

### Chapters 3-4

Next up, we move to the essence of the subject, where the concepts of vector spaces, independence of vectors, basis and dimension of a space, and the general overview of the four fundamental subspaces (rowspace, columnspace, nullspace and left nullspace) of a matrix are introduced. Further, the author introduces the concept of orthogonal subspaces, uses it to develop the intuition regarding projection of vectors and therefore matrices. These concepts are then applied to finding the least squares approximation to regression problems, and the connection between the least squares error criterion and the left nullspace of a matrix is shown. `Gram-Schmidt` process is another important concept presented. This material essentially wraps up with what the author calls the `Fundamental Theorem of Linear Algebra`, with the general idea regarding the dimensionality and orthogonality of the aforementioned subspaces. Probably the most important section of the book, which is developed further in the next couple of chapters.

### Chapter 5

Primarily deals with the properties of determinants of matrices, and the formulas derived from using those properties are presented as intuitive generalizations. Want to know how determinant formula you learnt back in high school came to be? Want to know the geometric meaning of the determinant of an n-dimensional matrix? Want to revisit the old formulas that you once read about, but found exceedingly dry back in school? Give this chapter a solid read.

### Chapter 6

Formally wraps up the conceptual journey presented by the book, and is the most important chapter in the entire manuscript in context of machine learning. Most of the ML that we see today is heavily influenced and derived as a result of the properties of eigenvalues and eigenvectors of the matrices that we model the real world problems on. This chapter formally marks the end of the first half of the book, and only the applications of the concepts presented until then are exposited in the following material. Be sure not to miss a single concept presented here, it will only come back to haunt you later.

### Chapters 7-12

Heavy on applications of the concepts introduced in the first half. `Singular Value Decomposition`, `Principal Components Analysis`, `Linear Transformations`, `Fast Fourier Transforms`, applications in computer graphics, cryptography and so on, are covered in heavy detail. The last chapter also doubles up as a subtle introduction to the use of linear algebra in probability theory. While I might suggest to read specific portions from the said chapters, it might be in your interest to cover these depending on your field of interest. You might also be tempted to skip a few chapters in between, and I don't personally think you would be missing a lot of conceptual understanding while doing so.


In conclusion, I would also like to mention that Prof. Strang's [MIT OCW course](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/index.htm) (from 2010) contains a much faster explanation to the text, and is a nice alternative to those who do not have a lot of time on their hands to spare. Be advised, the text covers some material he doesn't teach in his course, and vice versa.

**Let's Cut The Check For Now, Shall We?**