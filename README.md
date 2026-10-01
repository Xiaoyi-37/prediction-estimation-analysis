# Do Better Predictions Imply Better Estimation?

A simulation study examining whether better predictive performance necessarily leads to better statistical estimation.

## Overview

This project was completed for **MATH 525: Sampling Theory** at McGill University.

Using a simulated finite population, we compared prediction and estimation performance under three settings:

- Model-assisted estimation
- Missing-data imputation
- Reweighting / inverse probability weighting

For each setting, repeated simple random samples were drawn and multiple statistical and machine-learning models were evaluated using mean squared error (MSE). :chatgpt-content-reference{index="0"}

## Methods

The simulation used:

- Population size: **1,000,000**
- Sample size: **10,000**
- Monte Carlo iterations: **1,000**
- Simple random sampling without replacement
- Missing outcomes generated under a covariate-dependent mechanism

Models included:

- Linear and Logistic Regression
- K-Means
- K-Nearest Neighbors
- Neural Networks
- Random Forest
- Natural Cubic Splines

## Key Findings

The relationship between prediction and estimation depended on the estimation method.

- **Model-assisted estimation:** better prediction was associated with better estimation.
- **Imputation:** better prediction did not always produce a better estimator, although very poor predictive models generally performed poorly in estimation.
- **Reweighting:** prediction accuracy and estimator performance could differ substantially.

Overall, **better predictive accuracy does not necessarily imply better estimation performance**. :chatgpt-content-reference{index="1"}

## Tools

R · Monte Carlo Simulation · Survey Sampling · Missing Data · Predictive Modeling

## Authors

- Helen Bian
- Xiaoyi Xu
- Kadira Jones

Collaborative course research project for **MATH 525: Sampling Theory, McGill University**.
