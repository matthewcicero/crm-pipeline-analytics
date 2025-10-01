```markdown
# CRM Pipeline Analytics (Synthetic Data)

Small project to show how CRM sales data can be analyzed for funnel health, revenue, and hygiene metrics.  
Built with a synthetic dataset that mimics Salesforce/HubSpot exports (no real PII).

---

## 🗂 What's Inside
- `/data/synthetic_pipeline.csv` → dummy leads with stages (appt → show → qualified → proposal → closed_won), deal sizes, cycle time, hygiene fields  
- `/notebooks/pipeline_metrics.ipynb` → analyzes the CSV and prints funnel metrics  
- `/notebooks/generate_synthetic_crm.ipynb` → generator for new synthetic data  
- `/assets` → optional images/plots

---

## ⚡ Quickstart
1. Open `/notebooks/pipeline_metrics.ipynb` on GitHub to view
2. Or run in Google Colab:
   - Upload `synthetic_pipeline.csv`
   - Run all cells

---

## ❓ Why Synthetic?
This dataset was generated for demo purposes. The same code could run on a real CRM export (Salesforce, HubSpot, etc.) with minimal changes.
