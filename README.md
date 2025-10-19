# CustomerOrders

A small PySpark + Gradio project that demonstrates transforming and exploring a simple dataset of customers, orders and products. This repository contains two Jupyter notebooks: one for data transformation using PySpark and one that exposes a small Gradio app for interactive exploration.

Contents
--------
- code/
  - `PySpark_Transform.ipynb` — data ingestion and transformation using PySpark. Reads `data/Customer.xlsx`, `data/Orders.json` and `data/Products.csv`, normalizes and joins them, and writes out analysis-ready tables.
  - `PySpark_Gradio_APP.ipynb` — a notebook that builds a lightweight Gradio UI to explore the transformed data (filters, summaries, simple visualizations).
- data/
  - `Customer.xlsx`, `Orders.json`, `Products.csv` — sample datasets used by the notebooks.

Quick start
-----------
Prerequisites

- Python 3.8+ (3.10 recommended)
- pip

1. Create a virtual environment (recommended):

	python -m venv .venv
	source .venv/bin/activate

2. Install dependencies:

	pip install -r requirements.txt



Contact / Contribution
----------------------
Contributions welcome — open an issue or submit a PR. If you want help packaging this as a small CLI or web app, tell me which format you prefer.

---
Generated/updated by the repository maintainer tools.
