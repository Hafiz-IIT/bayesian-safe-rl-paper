# Experiment protocol — Bayesian uncertainty and action gating

## Claim under test
An uncertainty-aware gate may reduce false authorization near a risk threshold at the cost of additional verification or blocking.

## Data generation
Create labelled scalar hazard scenarios with known generating distributions. Include well-specified and misspecified priors, varied observation noise, and shifted test distributions.

## Baselines
Point-estimate thresholding, fixed conservative margin, and posterior-interval gating.

## Metrics
False-allow rate, false-block rate, verification rate, total intervention rate, interval coverage, calibration error, and decision cost under an explicitly stated cost matrix.

## Statistical reporting
Use multiple fixed seeds and report confidence intervals. Separate calibration data from test data. Include threshold-near cases and negative results.

## Current evidence
The code implements a scalar conjugate posterior update and a three-way threshold gate. It is not a complete Bayesian RL agent and no safety guarantee is claimed.
