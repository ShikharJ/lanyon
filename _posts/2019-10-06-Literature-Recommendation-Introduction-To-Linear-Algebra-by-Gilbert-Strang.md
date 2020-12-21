---
layout:	post
title: Literature Recommendation - Introduction To Linear Algebra by Gilbert Strang
---

<a href="//wellesleypublishers.com" target="_blank">
	<img align = "middle" src = "/assets/ILAGS.png">
</a>

For those of you greenhorns that have just made your venture into the world of machine learning, it must not come as a surprise to you that linear algebra is the purest soul of the realm. Most of the ML and optimization world borrows ideas heavily from the same, and it is single-handedly the most important area of mathematics that will dictate your level of thinking while tackling ML problems.

As such, it is altogether fitting to write about a text that has probably helped thousands of undergraduates to get up and running with their knowledge of linear algebra. Prof. Gilbert Strang's book is one such epitome of awesome insights into the field. There are probably very books out there that are worth reading over and over again, Strang's book being one such gem. I have personally read this book many times over the course of my undergrad, and have always felt that I learnt something completely new each time. I would not be exaggerating if I said that you should keep this book in your personal collection of self-help books. Here are some of the points which I must mention, which make it such an important read.

## The Writing Style
Strang takes up a non-rigorous approach to teaching the subject. He mentions a concept dead straight, tells you why it is important and mentions how it relates to the bigger picture of algebraic and geometric meaning. Very few formal proofs are provided in the text, with the author emphasizing on the importance to derive the non-rigorous connections to other fields of mathematics. 

While many professionals would argue that this method of teaching is specifically aimed at non-mathematicians (since the flavour is rather numerical than theoretical), I personally think this is an amazing way to approach a deeply theoretical subject without having to raise the bar of abstraction to the level that is incomprehensible to most people. If you have read any standard book on abstract algebra, you would notice that linear algebra and vector fields are typically not even introduced in the first ten or so chapters. This leads to a huge jump in abstraction that most undergraduates would not be prepared to handle. That being said, one should first strive to master the concepts introduced in the text before moving on to a more theory oriented text. The book is entirely self-contained, and the recommended way to learning the material would be to rather forget the concepts of matrices and determinants that one learns during the typical high school system, and approach the book with a fresh mind.

## Important Sections

### Chapters 1-2

The first couple of chapters act as a refresher material for the concepts of vectors, coordinate geometry and matrix operations that a student typically learns during their high school, while introducing the concepts of `Gaussian` elimination techniques for solving systems of equations. Extremely insightful and important, especially from a standpoint of numerical linear algebra.

### Chapters 3-4

Next up, we move to the essence of the subject, where the concepts of vector spaces, independence of vectors, basis and dimension of a space, and the general overview of the four fundamental subspaces (rowspace, columnspace, nullspace and left nullspace) of a matrix are introduced. Further, the author introduces the concept of orthogonal subspaces and uses it to develop the intuition regarding projection of vectors and therefore matrices. These concepts are then applied to finding the least squares approximation to regression problems, and the connection between the least squares error criterion and the left nullspace of a matrix is shown. `Gram-Schmidt` process is another important concept presented. This material essentially wraps up with what the author calls the `Fundamental Theorem of Linear Algebra`, with the general idea regarding the dimensionality and orthogonality of the aforementioned subspaces. Probably the most important section of the book, which is developed further in the next couple of chapters.

### Chapter 5

Primarily deals with the properties of determinants of matrices, and the formulas derived from using those properties are presented as intuitive generalizations. Want to know how determinant formula you learnt back in high school came to be? Want to know the geometric meaning of the determinant of a matrix of arbitrary order? Want to revisit the old formulas regarding the properties of determinants that you once read about, but found exceedingly dry back in school? Give this chapter a solid read.

### Chapter 6

Formally wraps up the conceptual journey presented by the book, and is the most important chapter in the entire manuscript in context of machine learning. Most of the ML that we see today is heavily influenced and derived as a result of the properties of eigenvalues and eigenvectors of the matrices that we model the real world problems on. The focus is mostly on real symmetric matrices in this chapter, with general matrices and complex eigenvalues given formal treatment later in the book. Some important concepts would be the diagonalization criterion of matrices, the properties of matrices sharing similar eigenvalues and eigenvectors, and most importantly the `Spectral Theorem` and its consequences when it comes to positive definiteness. The material is covered in a fashion that treats matrices as simple variables, while making use of powers and exponentiation to solve differential equations. This also formally marks the end of the first half of the book, and only the applications of the concepts presented until then are exposited in the following material. Be sure not to miss a single concept presented here, it will only come back to haunt you later.

### Chapter 7

`Singular Value Decomposition` is the central idea in linear algebra. While diagonalization exists only for a certain type of matrices (whose algebraic and geometric multiplicities are the same), SVD is a much more powerful concept which applies to all matrices. The concept of single basis diagonalization introduced earlier, and applied to real symmetric matrices in `Spectral Theorem` gets generalized to the idea of two-bases diagonalization in SVD. Furthermore, this concept is heavily utilized in the decomposition of higher dimensional matrices (called tensors), and is aptly called `Higher Order Singular Value Decomposition` or HOSVD. `Principal Components Analysis` is another major application of SVD, used heavily in dimensionality reduction in ML. The chapter wraps up with an explanation of the effect of multiplying a matrix with a vector, and the use of pseudoinverse for a reverse analogy.

### Chapter 8
`Linear Transforms`, `Fourier Series`, `Jordan Forms` and change of basis are some of the topics covered here. The connection between `Fourier Series` and vector expansion in an orthonormal basis, inner product between functional basis vectors and so on is also exposited nicely. This chapter particularly focuses on the origin of matrix objects while computing linear transformations, and goes on to apply the same on some carefully chosen examples.

### Chapters 9-12

Heavy on applications of the concepts introduced in the first half. `Fast Fourier Transforms`, `Linear Programming`, applications in computer graphics, cryptography and so on, are covered in detail. The applications are introduced as generalizations of the previously introduced concepts.  The last chapter also doubles up as a subtle introduction to the use of linear algebra in probability theory. While I might suggest to read specific portions from the said chapters, it might be in your interest to cover these depending on your field of interest. You might also be tempted to skip a few chapters in between, and I don't personally think you would be missing a lot of conceptual understanding while doing so.


In conclusion, I would also like to mention that Prof. Strang's [MIT OCW course](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/index.htm) (from 2010) contains a much faster explanation to the text, and is a nice alternative to those who do not have a lot of time on their hands to spare. Be advised, the text covers some material he doesn't teach in his course, and vice versa. A curious student may also wish to venture into Serge Lang's `Introduction to Linear Algebra` for certain topics that Strang does not cover.

**Let's Cut The Check For Now, Shall We?**