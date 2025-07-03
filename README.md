# 📊 Vendor Performance Analysis

This project performs an end-to-end analysis of vendor performance using procurement data. It includes data ingestion from SQLite, exploratory data analysis (EDA), KPI computation, and reporting using Python.

The goal is to help businesses make data-driven decisions by identifying high-performing and underperforming vendors based on key metrics like stock turnover, purchase contribution, and more.

---

## 🧰 Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **SQLite3**
- **Matplotlib / Seaborn** (for visualizations)
- **Logging** (for tracking ETL steps)

---

## 🏗️ Project Structure
Vendor_Performance/
│
├── data/ # Raw SQLite database or CSVs
├── notebooks/
│ └── vendor_analysis.ipynb # Main analysis notebook
├── scripts/
│ ├── ingestion_db.py # Script to ingest data from SQLite
│ └── get_vendor_summary.py # Vendor summary generation
├── README.md

## 📈 Key KPIs Generated

- **Stock Turnover**
- **Purchase Contribution**
- **Average Purchase Price by Vendor**
- **Top/Bottom Performing Vendors**
- **Cost vs Volume Trends**

- ✅ Outcomes
Identified vendors with low stock turnover

Analyzed purchase cost contributions

Enabled vendor performance scoring

Provided insights for procurement optimization

