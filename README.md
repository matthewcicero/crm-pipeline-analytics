# CRM Pipeline Analytics (Synthetic)

📊 Safe, synthetic CRM dataset + notebook for analyzing funnel health, revenue, and hygiene metrics.

## What's inside
- **/data/synthetic_pipeline.csv** — generated dummy leads with stages (appt→show→qualified→proposal→closed_won), deal sizes, cycle time, and hygiene fields
- **/notebooks/pipeline_metrics.ipynb** — loads the CSV, prints key conversion metrics, and plots one chart
- **/notebooks/generate_synthetic_crm.ipynb** — optional generator that produces the synthetic dataset
- **/assets/** — images or plots (if you save charts later)

## Quick start
1. Open `/notebooks/pipeline_metrics.ipynb` on GitHub to view
2. To run in Colab: upload `synthetic_pipeline.csv` when prompted in Cell 1

## Why synthetic?
This mimics a Salesforce/HubSpot export but contains no real PII. The same code would work on a real CRM dataset.
