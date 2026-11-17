---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

## Publications
---

Kicking for Goal or Touch? An Expected Points Framework for Penalty Decisions in Rugby Union
------
*Published in the Journal of Quantitative Analysis in Sports (JQAS), 2026*

The first application of an Expected Points framework to rugby union. Our paper builds decision maps showing when a team should kick for goal versus kick to touch after a penalty, conceptually similar to fourth-down decision models in the NFL.

[Read the paper here &rarr;](https://www.degruyterbrill.com/document/doi/10.1515/jqas-2025-0183/html)


A Dynamic Rating System for NFL Pass Rushers and Blockers
------
*Published in the Wharton Sports Analytics Journal, 2026*

A framework for rating NFL offensive and defensive linemen using player tracking data and individual play interactions, combining Multinomial ELO and Ridge Regression approaches. Presented as a poster at the New England Symposium on Statistics in Sports (NESSIS) at Harvard University and at the Wharton Sports Business Summit.

[Read the paper here &rarr;](https://wsb.wharton.upenn.edu/opponent-adjusted-evaluation-of-nfl-pass-blocking-and-pass-rushing-performance/)



## Pre-Prints
---


Modeling the Joint Distribution of Box Score Statistics: A Gaussian Copula Approach
------

What is the probability that LeBron James records at least 27 points, 7 rebounds, and 7 assists tonight? While an interesting statistical question by itself, the rise of sports betting and multi-leg parlays has made answering this question increasingly relevant. However, coming up with an estimated likelihood is tricky, since box score statistics aren't independent. We estimate the joint probability that a player reaches a combination of thresholds in points, assists, and rebounds using a Gaussian copula, fit separately for each player using only their previous games.


[Read the paper on arXiv &rarr;](https://arxiv.org/abs/2611.10152)


A Markov Chain Approach to Modeling Rugby Union
------

Win probability tells us how likely a team is to win, but says little about how the rest of the match might play out. We develop a Markov chain model for rugby union that follows changes in score, time, field position, and possession, with transition probabilities estimated from phase-level match data. The same model lets us estimate win probabilities and expected points, calculate distributions for the next score and final margin, and simulate the remainder of a match from its current state. We assess predictive accuracy and calibration on 27 held-out matches after fitting the model to 105 matches from the same season. The model achieves similar test error to logistic regression and XGBoost, showing that we can model the progression of play while remaining competitive with methods that predict final outcomes directly.

[Read the paper on arXiv &rarr;](https://arxiv.org/abs/2610.04813)

Dummy RAPM
------

We introduce Dummy RAPM, an incremental improvement to RAPM which explicitly includes the
count of excluded low-minute players on the court for each team as an additional regressor. Rather
than allowing excluded players’ contributions to be silently redistributed across the design matrix, this
approach isolates their effect into 5 coefficients (representing 5 possible numbers of low-minute players
in a single lineup), preventing it from contaminating the estimates of retained players. We find that this
reallocation yields improved out-of-sample predictive performance than a standard RAPM model.

[Read the paper on arXiv &rarr;](https://arxiv.org/abs/2608.19454)
