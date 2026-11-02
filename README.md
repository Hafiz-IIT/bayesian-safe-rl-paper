# Bayesian Linear Models as Priors for Safe Reinforcement Learning in Robotics

**Status: manuscript in preparation; not submitted or published.**

This repository contains manuscript source and an experiment protocol for evaluating uncertainty-aware decision gates in autonomous control.

## Files
- paper/main.tex — manuscript source
- paper/EXPERIMENT_PROTOCOL.md — synthetic data, baselines, metrics, and stress tests
- modular notes in paper/ — abstract, method, claims, limitations, reproducibility
- Makefile — local PDF build target

## Build
Requires LaTeX with geometry, AMS math, booktabs, and hyperref packages.

    make pdf
    make clean

## Evidence boundary
The companion lab implements a scalar Normal-Normal posterior update and ALLOW/VERIFY/BLOCK heuristic. It is not a complete Bayesian RL system, calibrated safety certificate, or robotic deployment. No empirical safety claim is made.

Companion code: https://github.com/Hafiz-IIT/bayesian-safe-rl-lab
