# STAT 447C Project (Bora and Damien)

# Basic requirements

## Team is identified.
Bora Guney, Damien Fung

## The proposal identifies which of the project themes it will address.
Bayesian vs Frequentist AND Bayesian regression and classification

## There is a working link to a public repo containing commits from all team members.
https://github.com/YellowPrawn/STAT-447C-Project-Bora-and-Damien-/tree/main

## Two real-world candidate datasets appropriate for the selected theme are clearly described (e.g. a URL, showing the structure or head of a dataframe).
https://www.spglobal.com/spdji/en/indices/equity/sp-500/#overview

We are using two candidate datasets from the same source. We consider data from both a 3 year span, and a 5 year span. We believe that these two datasets are different enough despite the 3 year dataset being a subset of the 5 year dataset. This is because the 5 year dataset includes data pre-pandemic, which shows a noticeable drop in the time series moving average whereas the 3 year dataset does not. The presence of the effects of COVID-19 are likely to yield largely different models; both datasets would be interesting independently of each other.

## A short summary of potential approaches to tackle the project theme.
We plan to use multiple steps in our analyses. Firstly, we need to establish a general time series forecasting model that would be appropriate for the data at hand. Then, we can make our prior choices for the various parameters of the model (i.e. intercept, slope, standard deviation, etc). Then, we will apply two different cross validation schemes to fulfill the Bayesian vs Frequentist theme; namely Monte Carlo Cross Validation (Bayesian) vs standard k-Fold Cross Validation (frequentist). We will use the results from both cross validation schemes to compare the estimated model performance against the true performance values, the model parameters, and the performance of the estimate with the chosen model parameters from each scheme.


## If it is a team project, the proposal contains a short plan for ensuring the two team members will contribute roughly equally.
We will collaborate on the analysis/code implementation together, Bora will work on the conclusion of the report and Damien will work on the introduction.
