# Clustered Data and Linear Models: Avoiding the Traps 

This repository contains the code used to write the Medium article *Clustered Data and Linear Models: Avoiding the Traps*. The article explores techniques to handle clustered data when fitting linear models, addressing common pitfalls that arise when residuals are not independent and identically distributed (i.i.d.).

## Article Overview

In the article, we examine how clustering can violate linear model assumptions and introduce three methods to address this issue:

1. **Fixed-Effects Model**: Controls for group-specific characteristics, focusing on within-group variation.
2. **Clustered Standard Errors**: Adjusts standard errors to account for within-group correlation without changing model estimates.
3. **Mixed-Effects Model**: Accounts for both within-group and between-group variation with random effects.

Each method is demonstrated with a simple example involving test grades and study hours across multiple schools, highlighting the trade-offs of each approach.

##  Reading

For full details and analysis, read the Medium article [here](https://medium.com/@JuanPabloHerrera/clustered-data-and-linear-models-avoiding-the-traps-2-2-365309be72f6).

---

