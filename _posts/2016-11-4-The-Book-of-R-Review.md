---
layout: post
title: The Book of R - Review
---


# The Book of R Review

[This](https://www.nostarch.com/bookofr) is a nice big book, useful for beginners of both statistics and R programming. Intermediate users can use the book as a desktop reference with a particular emphasis on generating statistical plots. It cannot substitute a good statistics textbook but it provides a coverage of the subject from the basic concept of probability to hypothesis testing, ANOVA, statistical modeling and more. The [author](http://www.stats.otago.ac.nz/?people=tilman_davies) states from the beginning that his book follows a frequentist approach to statistics; if the reader is interested in an introduction to statistics which follows a bayesian perspective there are other more appropriate choices ( e.g. [Doing Bayesian Data Analysis: A Tutorial with R and BUGS by John K. Kruschke](https://sites.google.com/site/doingbayesiandataanalysis/) ).

The book is organized in twenty-six chapters further collected into five parts, each chapter is accompanied with exercises and a list of references to the important code used. The first and second part introduce the R programming language depicting how to write programs and visualize data. The third and fourth part are dedicated to statistics, from the basics (elementary statistics and probability) to the most common statistical procedure used in the field. The fifth part indicates advanced techniques for visualizing data. Furthermore there are two appendices providing a short guide on installing and operating R packages (Appendix A) and introducing the reader to R Studio, a commonly used IDE for R (AppendixB).

Part I (chapters 1 to 7) covers the basics of R as a programming languages presenting all the different data types available (vectors, matrices, data.frames, etc), how to import, save data and produce basic plots using both the R classic graphics and the _ggplot2_ package.

Part II (chapters 8 to 12) provides the necessary information to start developing in R: conditions, loops, calling and creating functions, exceptions handling are presented with notes and exercises.

Part III (Chapters 13 to 16) covers the basics of statistics, following a frequentist approach. It is devoted to probability, distributions and basic EDA techniques and visualizations.

The next part (chapters 17 to 22) presents advanced statistical techniques such as statistical testing and modeling.
Chapter 17 introduces the concepts of _sampling distribution_ and _confidence intervals_. Chapter 18 depicts the most common concepts and the limitations of frequentist _hypothesis testing_ ,dealing with significance values, errors and Power. Chapter 19 is dedicated to the Analysis of Variance (ANOVA), extension of the hypothesis testing for multiple means, in both comparing means split by one categorical variable (one-way ANOVA) and split by multiple categorical variable (multiple-factor ANOVA). Chapter 20 introduces the important topic of linear regression for evaluating how variable relate to each other, followed by chapter 21 where the simple linear regression methods are extended to measure the joint effect of multiple variables (multiple linear regression). Finally in chapter 33 the author discuss how to choose an appropriate model for the analysis and validate the assumptions made during this selection.

Part V is devoted to advanced graphics techniques and can be seen as a selling point for both novice and intermediate users. More in details, chapter 23 shows how to customize your plots using the base R graphics and goes from device handling to a fully annotated scatter plot (layout, fonts, formulas, etc.). Chapter 24 goes into details in using the _ggplot2_ package to produce expressive plots and introduces the _ggvis_ package for building interactive graphics using a syntax similar to _ggplot2_. Chapter 25 presents a detailed explanation in using colors in R followed by a series of paragraphs presenting static plots in higher dimensions such as 3D scatter plots, contours and perspective plots. Chapter 26 is focused on how to produce interactive 3D plots using the the _rgl_ package. Furthermore, a short color insert shows several statistical plots depicted in the previous two chapters.

In summary, this weighty book (almost 800 pages) covers a lot of ground presenting the material properly, with useful notes, exercises  and clear code. I recommend this book to both beginners, as a good introduction to basic statistics and R, and to intermediate users as a desktop reference to assist in performing day-to-day analysis.


__Disclaimer__: No Starch Press provided me a free copy for review.
