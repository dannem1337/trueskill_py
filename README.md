# Trueskill Bayesian Ranking System

In this project, we aimed to estimate the player's skill in a competitive setting using
probabilistic machine learning specifically the TrueSkill Bayesian ranking system
developed by Microsoft. The model used represents the player's skills as Gaussian
random variables and Bayesian inference is used to compute the posterior distribution of these skills.
The model was initially tested on the Serie A football dataset from 2018/2019, 
but was later adapted for application to the UFC dataset for match-ups from 1993-2021.

Run the entire notebook to reproduce all results and figures for these questions. 

N.B The cell UFC fights dataset requires a very long running time, approx 1 hour, in order to estimate the skill level of all fighters.

The work of this project is based on [Microsofts TrueSkill ranking system]{https://www.microsoft.com/en-us/research/project/trueskill-ranking-system/}.
