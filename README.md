# Econometric Analysis Project: FWL and linearity

## Overview
This repository contains a Jupyter notebook that explores basic econometric concepts using simulated data.

The project focuses on:
- Illustration of the Frisch-Waugh-Lovell (FWL) theorem and its implications for linear regression both when the variables have a linear relation and when this does not happen.

## Objective
The goal of this project is to demonstrate how classical econometric results arise in practice and to discuss their limitations when moving beyond linear settings.

## Methods
The analysis includes:
- Data generation (simulated dataset)
- Exploratory data analysis (summary statistics and visual inspection)
- Linear regression models
- Application of the Frisch-Waugh-Lovell theorem
- Discussion of conditions under which the equivalence between full and partial regressions holds

## Key Insight
The project shows that the equivalence between full and partial regression coefficients holds under linear conditional expectations, while deviations from linearity may require more flexible (nonparametric or machine learning-based) approaches.

## Requirements
The following Python libraries are used:
- numpy
- pandas
- matplotlib
- seaborn
- statsmodels
- scikit-learn
- doubleml

## Structure
- `fwl_and_linearity.ipynb`: main analysis and implementation

## Notes
This is a learning-oriented project aimed at strengthening understanding of econometric theory
