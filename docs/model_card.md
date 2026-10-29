# Model card — Retail Demand Forecasting and Inventory Optimization

Task: retail; source: Synthetic store-level demand and promotion data.

## Evaluation
- Random Forest: 1 − WAPE = 0.9071
- Seasonal naive: 1 − WAPE = 0.8219

Split: chronological last 90 days. The supplied results are deterministic educational demonstrations, not real-world benchmarks or deployment approvals.

## Risks
Training data is synthetic. Statistical estimates may not transfer to real events. Audit fairness, calibration, input distributions, access controls and domain-specific safety before external use.
