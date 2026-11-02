# Results directory

No calibration or safety benchmark results are claimed yet. Use the protocol in paper/EXPERIMENT_PROTOCOL.md.

Expected files:
- experiment_config.json — prior parameters, observation model, risk threshold, cost matrix, and seeds
- summary.csv — gate metrics by prior specification, noise level, and shift condition
- calibration/ — interval coverage and calibration diagnostics
- analysis.md — false authorization, false blocking, verification trade-offs, and limitations

Required metrics include false-allow rate, false-block rate, verification rate, interval coverage, calibration error, and intervention cost. A scalar posterior interval is not a safety certificate.
