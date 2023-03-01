---
id: phpaqj29qeulvsvdmrbkp7o
title: DS Notes
desc: ''
updated: 1677634486609
created: 1677615896190
---
## Introduction

In data science applications, it is very common to be interested in the relationship between two or more variables. `Linear Regression` is commonly used to quantify the relationship between two or more variables. It is also used to adjust for `confounding`. Linear regression is a powerful technique for removing confounders, and it is essential to understand when it is appropriate to use. 

In future chapters we examine a case study relating to the data-driven approach used to construct baseball teams described in the book (and movie) Moneyball.
> `1` how to implement linear regression

We will try to determine which measured outcomes best predict baseball runs and to do this we'll use linear regression. 
> `2` adjust for confounding in practice using R

We will also examine confounding, where extraneous variables affect the relationship between two or more other variables, leading to spurious associations. 

## Learning goals:

> 1. How linear regression was originally developed by Galton
> 2. What confounding is and how to detect it
> 3. How to examine the relationships between variables by implementing linear regression in R

## There are 3 major sections in this course


**Introduction to Linear Regression**

> 1. basics of linear regression 
> 2. example: data-driven approach used to construct baseball teams
> 3. correlation
> 4. correlation coefficient
> 5. stratification
> 6. variance

**Linear Models**

> 1. least squares estimates
> 2. multivariate regression
> 3. several useful features of R, such as - tibbles, lm, do, and broom
> 4. how to apply regression to baseball to build a better offensive metric

**Confounding**

> 1. confounding
> 2. reasons that correlation is not the same as causation, such as spurious correlation, outliers, reversing cause and effect, and confounders
> 3. Simpson's Paradox