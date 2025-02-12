# vaccine_trial_simulation
This repository contains a computational approach to evaluate a veterinary vaccine trial for Hepatitis E in pigs. The project focuses on determining the sample size (N) of both treatment groups required to achieve a 90% chance of detecting a statistically significant reduction in infection rates, using a permutation test.

### Project Overview

The problem assumes:

* The probability of infection for untreated pigs is pc = 0.5.

* The probability of infection for vaccinated pigs is pv = 0.1.

* Statistical significance is evaluated at the α = 0.05 level.

The objective is to:

1. Simulate infection outcomes for control and treatment groups.

2. Implement a permutation test to evaluate differences in infection rates.

3. Determine the sample size  that provides a 90% chance of detecting a significant reduction in infection rates.

### Key Features

* Simulation Function: Simulates infection outcomes using random probabilities.

* Permutation Test: Performs a statistical test to assess the significance of infection rate differences.

* Sample Size Analysis: Uses iterative simulations to identify an optimal sample size.

* Visualization: Provides plots to help interpret the results and validate findings.

### Repository Structure

* README.md: Project documentation (this file)

* vaccine_trial_simulation.ipynb: Main Jupyter Notebook containing the implementation, analysis, and results.
