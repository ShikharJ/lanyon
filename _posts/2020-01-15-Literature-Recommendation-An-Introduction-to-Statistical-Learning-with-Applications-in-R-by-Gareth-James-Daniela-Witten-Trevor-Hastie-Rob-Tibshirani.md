---
layout:	post
title: Literature Recommendation - An Introduction to Statistical Learning with Applications in R by Gareth James, Daniela Witten, Trevor Hastie and Rob Tibshirani
---

<img align = "middle" src = "/assets/AISLAR.png">

This post should formally begin with a disclaimer, this book is merely intended as a rather easy introduction to applying Statistics and Probability in solving certain problems in Machine Learning. The authors themselves mention that the manuscript was developed as a gentler-sloped prequel to their seminal work `The Elements of Statistical Learning` by Hastie, Tibshirani and Friedman, which is a rather heavy-hitting book when it comes to mathematical density and depth.

While the book doesn't mention any essential prerequisites, I would strongly recommend having prior familiarity with undergraduate level Probability theory, as the book only explains the concepts in passable manner. The chapters are pretty self-contained and can make up for really quick reads. Most of the material covered is a smaller, toned-down, applied version of the mathematical machinery depicted in the book mentioned above. The text is almost purely devoted to supervised learning, with unsupervised methods being introduced only towards the very end.

## The Writing Style
Since the focus is on Applied Machine Learning, there aren't any proofs provided in the text. Also, throughout the text, the authors openly mention a concept without ever diving into it, or providing an idea behind the formulation. Concepts like `Confidence Interval`, `P-Value` and so on are freely used without providing a procedure for calculating them manually. While this can surely be a frustrating experience for less experienced people or folks who have learned and forgotten most of these concepts, the text still provides a reasonable amount of illumination when it comes down to individual topics, which are segregated into separate chapters for a better treatment. Overall, the book is a quite smooth read which focuses on breadth over depth, and shouldn't pose much of a challenge to a sophomore level student of undergraduate CS. 

## Important Sections

### Chapters 1-2

The first couple of chapters focus on the overview of the field of `Statistical Learning`, as well as the notational semantics followed in the text. Broader explanations and examples of `Supervised and Unsupervised Learning`, `Prediction vs. Inference` dilemma, `Parametric and Non-Parametric` methods and `Regression vs. Classification` paradigms are provided. The second chapter ends with an introduction to the `Bias-Variance Tradeoff`, and how it comes into the broader picture of performance of statistical models. The later part of the book makes steady usage of the above terms in explaining most of the phenomenon that we encounter later.

### Chapter 3

Next, we move onto introductory `Regression Theory`, which later gets applied for classification tasks in the next chapter, albeit with some minor subtleties. The initial exposition, along with the example of a single variable regression setting, is complimented with methodology of calculating coefficients estimates, as well as their `Confidence Intervals` using `Standard Error` estimates. `Null and Alternate Hypothesis`, `T-Statistic` and `P-Value` are also some important concepts introduced. The multivariate linear regression model is also developed from the single variable model, along with its set of measures for hypothesis testing. These linear models are then extended to handle non-linear relationships through the use of composite, non-linear combinations of predictor variables, while focussing on the issues that arise with such approaches.

### Chapter 4

This section exposits the minor subtleties of extending the concepts of regression learnt previously in building classification models, namely through the `Logistic` model. This chapter also entails an introduction to `Bayesian Decision Theory`, mainly through the concept of `Likelihood Maximization` over `Gaussian` distributions, which is later used in explaining the rationale behind `Linear Discriminant Analysis` and its more flexible alternative - `Quadratic Discriminant Analysis`. The end subsection, detailing the performances of different methods on classification tasks under different settings is also particularly insightful.

### Chapter 5

While the previous sections focus mainly on the theory, this chapter mainly deals with the best practises when it comes to fitting the models on real world data. In `Statistical Learning Theory`, `Resampling` is an indispensable tool when it comes to assessing and selecting models. In situations where data is not abundant, certain strategies such as `Validation`, `K-Fold Cross-Validation` and `Leave-One-Out Cross-Validation`, can be an essential tradeoff between model performance and computational costs while measuring the accuracy of the models. `Bootstrap` is yet another important technique coming into play for estimating the uncertainity with model parameters. A deep understanding of the complete material here is absolutely essential.

### Chapter 6

In situations where the predictors outnumber the total observations, or where we simply wish to increase model interpretability through simplification, techniques such as `Subset Selection`, `Shrinkage / Regularization` and `Dimensionality Reduction` play a pivotal role. Such techniques also have their share of problems in the higher dimensional settings. Bear in mind that the authors of this book were also the original inventors of the `Lasso Regularization` technique and as such, their ideas are worth a strong look.

### Chapter 7

Next, we focus solely on extending our linear models, in order to equip them with more predictive power through `Polynomial Regression`, `Step Function` and `Local Regression`, `Splines` and `Generalized Additive Models (GAMs)`. Tibshirani and Hastie were also the original inventors of the GAMs, and have published a book on the topic as well, so it shouldn't come as a surprise that the coverage of the same is merely introductory in this chapter.

### Chapter 8

`Decision Trees` are one of the most powerful, yet intuitive, algorithms to be developed for classification and regression tasks. Unlike previous sections on linear models which are quite extensive, this section doesn't go much broader than explaining a few error indices for classification and regression setting, and contrasting with linear models. The chapter concludes with a rather useful introduction to `Bagging`, `Random Forest` and `Boosting` techniques, and the marked effect of these under various situations.

### Chapter 9

`Support Vector Machines (SVMs)` are one of the most important concepts in `Statistical ML`. SVMs were the state-of-the-art to beat all throughout the mid-1990s to the mid-2000s, right before the `Deep Learning` revolution took over. History has it that Vladimir Vapnik (the man behind the `Vapnik-Chervonenkis Theory` used heavily throughout `Statistical Learning`) had infact invented these techniques back in the early 1960s as a part of his Ph.D. thesis at Moscow University, but couldn't provide a proof of their empirical prowess, as they didn't have any computers to run his ideas on. Further on, when Vapnik submitted his work on SVMs to `Neural Information Processing Systems (NeurIPS)` conference, his ideas were rejected! SVMs are still heavily used in classical settings, where the data isn't quite plentiful. Any in-depth exposition of SVMs would atleast take a whole book, and as such, the chapter doesn't cover as much. However, it does an amazing job introducing `Maximal Margin Classifiers` and extending them into `Support Vector Classifiers` which later form the basis for `Support Vector Machines` and their similarity with `Logistic Regression`. Each sub-section of this chapter is worth a heavy read.

### Chapter 10

While the previous chapters solely focussed on the supervised learning paradigm, the last section introduces the nuances of the unsupervised setting, and its use in discovering novel characteristics and patterns in the data itself. `Principal Components Analysis` is exposited in more detail here, however, the manuscript still skips over a number of subtleties, and as such, this concept is better learnt elsewhere. The coverage on clustering techniques through `K-Means Clustering` and `Hierarchical Clustering`, and the shortcomings that accompany such procedures are well explained, and complete from the view of most practitioners, however.


In conclusion, I would like to mention that the fastest way of reading through this book is really to follow the examples given throughout the text and pondering over them, while simultaneously thinking of different general case situations. Additionally, one can simply work through the conceptual problems given at the end of each chapter. I personally found them to be rather easy flowing, though asking difficult questions wasn't the motive behind why this book was written in the first place. Those focussing on exploring Data Science as a full-time commitment would definitely benefit from this text. For such folks, working through the applied problems might be particularly enlightening as well.

**Rage Against The Machine Learning**