# Retail Demand Forecasting and Inventory Optimization — implementation notes

Data workflow: synthetic input generation → quality checks → train/validation split (chronological last 90 days) → task-specific baseline and alternative comparison → saved model/metrics → FastAPI inference → human interpretation.

Code: `engine.py`, `api.py`, `tests/test_project.py`. Execution: `python engine.py train`; tests: `python -m unittest discover -s tests -v`.

The task's original research brief describes optional advanced integrations; this repository implements a local reproducible demo, **not** live Kafka, production customer data, licensed medical images, real external embeddings or full MLflow platform.
