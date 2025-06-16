# LG-Inventory-Consolidation-Analysis-Project

# 📊 LG Inventory Consolidation and Analysis Project

This project is a real-world data cleaning and consolidation task provided by Randstad/GULP on behalf of LG Electronics. The objective is to process inventory data from three different customers and produce a consolidated inventory report grouped by LG model and store-level granularity using Python.

---

## 🧩 Problem Statement

We received 3 Excel files from 3 different LG customers, each with varying column formats and data quality. The challenge was to:
- Clean, normalize, and unify column formats across datasets
- Detect and handle missing, duplicate, and inconsistent values
- Consolidate the inventory based on LG **Model**, **EAN**, and **Store**
- Export key summary files and identify missing critical data entries
- Provide visualizations for business decision-making

---

## ✅ Key Deliverables

- ✔️ **Cleaned Datasets** for Customer A, B, and C  
- ✔️ **Merged Inventory File** with unified schema  
- ✔️ **Grouped Inventory Summary by EAN and Model**
- ✔️ **Store-Level Inventory Summary**
- ✔️ **Missing Value Report** for Model, EAN, and Inventory
- ✔️ **Bar Charts** to visualize inventory insights
- ✔️ **Process Log** documenting the automation steps

---

## 📁 Folder Structure

📦 LG-Inventory-Analysis

LG-Inventory-Analysis/
├── exports_YYYYMMDD_HHMMSS/ # Auto-generated folder with timestamped export files
│ ├── Inventory_By_EAN.xlsx # Inventory summary grouped by EAN code
│ ├── Inventory_By_EAN_Store.xlsx # Inventory grouped by EAN and store
│ ├── missing_model_or_ean_YYYYMMDD.xlsx # Log of records with missing model or EAN info
│ ├── top_10_models_chart.png # Bar chart of top 10 models by inventory count
│ ├── inventory_by_customer.png # Visual summary of inventory distributed across customers
│ └── log_YYYYMMDD.txt # Timestamped log file of the export run
├── LGProject.ipynb # Jupyter notebook containing data processing and analysis
├── requirements.txt # List of Python dependencies to run the project
└── README.md # Project description, structure, and usage instructions

