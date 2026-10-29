# Retail Demand Forecasting and Inventory Optimization — data dictionary

**Source:** Synthetic store-level demand and promotion data. Random seed 42. No actual customer, hospital or banking data.

| Feature | Notes |
|---|---|
| `lag7_sales` | Synthetic numeric training feature |
| `last7_mean` | Synthetic numeric training feature |
| `day_of_week` | Synthetic numeric training feature |
| `promo` | Synthetic numeric training feature |
| `day_index` | Synthetic numeric training feature |

Review the dataset generator in `engine.py` for exact distributions and assumptions.
