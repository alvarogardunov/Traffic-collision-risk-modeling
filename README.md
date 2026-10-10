# Traffic Collision Risk Modeling

A comparative binary classification and statistical modeling pipeline evaluating traffic collision outcomes using Generalized Linear Models (GLMs) in **R**.

## Overview
This project investigates traffic collision severity and outcomes using a robust dataset of over **290,000 observations**. By contrasting non-linear link functions against a baseline linear model, the analysis evaluates model performance, interpretability, and goodness-of-fit to determine the most effective predictive approach for collision risk.

## Methodology & Models
* **Logit Model (Logistic Regression):** Utilized a logit link function for binary classification, interpreting coefficients via odds ratios.
* **Probit Model:** Applied a cumulative normal distribution link function to analyze latent threshold effects.
* **Linear Probability Model (LPM):** Implemented an identity link baseline to benchmark parametric GLMs against ordinary least squares (OLS) assumptions.
* **Evaluation Metrics:** Assessed model performance using Akaike Information Criterion (AIC), log-likelihood values, and coefficient significance testing.

## Repository Structure
* `FinalProject.Rmd`: The source R Markdown file containing data preprocessing, model fitting, and diagnostic plots.
* `Final Project.pdf`: The compiled, full-length analytical report.

## Tech Stack
* **Language:** R
* **Libraries:** Base R stats packages, GLM implementations (`glm()`)
