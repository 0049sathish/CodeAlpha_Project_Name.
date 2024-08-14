# A/B Testing Simulation and Analysis

This repository contains a Python script for simulating and analyzing an A/B test using two groups of data. The analysis includes visualizing the data distributions, performing a t-test to determine statistical significance, and calculating the effect size using Cohen's d.

## Project Overview

A/B testing is a common statistical method used to compare two groups and determine whether there is a significant difference between them. In this project, we simulate data for a control group (Group A) and a treatment group (Group B) and analyze the results to draw actionable insights.

## Features

- **Data Simulation:** Generates random data for two groups with specified means and standard deviations.
- **Data Visualization:** Uses seaborn and matplotlib to visualize the distributions of both groups.
- **T-Test Analysis:** Performs an independent two-sample t-test to determine if the difference between the groups is statistically significant.
- **Effect Size Calculation:** Computes Cohen's d to quantify the magnitude of the difference between the two groups.
- **Actionable Insights:** Provides insights based on the statistical significance and effect size.

## Project Structure

```plaintext
├── ab_test_simulation.py   # Main script for the A/B test simulation and analysis
├── README.md               # Project description and instructions
└── requirements.txt        # Python dependencies
