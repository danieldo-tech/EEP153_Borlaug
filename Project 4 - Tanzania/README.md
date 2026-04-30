---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.17.1
  kernelspec:
    display_name: Python 3 (ipykernel)
    language: python
    name: python3
---

<!-- #region -->
# Project 4: Hacking Food and Nutrition

## Overview

This project analyzes food demand and nutrition outcomes for households in Tanzania. The goal is to estimate how households choose different foods based on prices, budgets, and household characteristics, then use those food choices to predict nutrient intake.

The project also compares predicted nutrition to recommended nutrition levels and tests simple policy options that could improve nutritional outcomes.

## Research Question

How can changes in household food budgets or food prices improve nutrition for Tanzanian households?

## Data

This project uses the following Tanzania datasets:

- Food Expenditures
- Food Prices
- Household Characteristics
- Food Composition Table

The expenditure data shows how much households spend on different foods. The price data helps convert spending into quantities. The household characteristics data describes each household. The food composition table shows the nutrients in each food.

## Methods

The project follows these steps:

1. Clean and prepare the Tanzania data.
2. Match foods across the expenditure, price, and nutrition datasets.
3. Estimate a food demand system using the `CFEDemands` package.
4. Predict household food expenditures and quantities.
5. Convert predicted food quantities into nutrient intake.
6. Compare predicted nutrient intake to recommended nutrition levels.
7. Identify the biggest nutritional deficiency.
8. Set a policy goal to reduce that deficiency.
9. Simulate sample policies
10. Compare which policy is more effective.

## Files

- `Project4.ipynb`: main notebook with the full analysis
- `README.md`: project description and instructions
- `test_project4.py`: unit tests
- Tanzania CSV files: raw data used in the analysis


## Main Outputs

The notebook creates:

- cleaned expenditure, price, household, and nutrition datasets
- estimated food demand system
- Frisch elasticity results
- predicted food quantities
- predicted household nutrient intake
- nutritional deficiency rates
- policy simulation results
- rough policy cost comparison
- final summary table


## Policy Goal

The project identifies the nutrient with the highest deficiency rate among households. The policy goal is to reduce that deficiency rate by half.

## Summary

This project shows how food demand estimates can be used to study nutrition policy. By connecting household food choices to nutrient intake, the analysis identifies a major nutritional challenge and compares different ways to improve household nutrition.
<!-- #endregion -->

```python

```
