# CRM Pipeline Analytics (Synthetic)

This project uses a synthetic CRM dataset to explore sales funnel health, revenue breakdowns, and hygiene metrics. It’s designed to mimic a Salesforce/HubSpot export while staying safe (no PII).

---

### 📂 What’s included
- **/data/synthetic_pipeline.csv** → dummy leads with stages (appt → show → qualified → proposal → closed_won), deal sizes, cycle time, hygiene fields  
- **/notebooks/pipeline_metrics.ipynb** → loads the dataset, calculates funnel conversion %, and produces simple plots  
- **/notebooks/generate_synthetic_crm.ipynb** → generator script for creating the synthetic dataset  
- **/assets/** → saved plots or charts  

---

### ⚡ Quick start
1. Open `notebooks/pipeline_metrics.ipynb` on GitHub to preview results  
2. Or upload `synthetic_pipeline.csv` into Colab and re-run the notebook  

---

### 📊 Example output
- Leads in dataset: ~500  
- Funnel conversion:  
  - Appt set → show: 68%  
  - Show → qualified: 55%  
  - Qualified → proposal: 48%  
  - Proposal → closed_won: 22%  
- Revenue leaders by rep: Owner_2 and Owner_4  
- Top source: Referrals  

*(numbers above will change if you regenerate synthetic data)*  

---

### ❓ Why synthetic?
The dataset is randomly generated but follows realistic CRM structure. The same notebook logic could be applied to a real CRM export from Salesforce or HubSpot.
