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


- `exports_YYYYMMDD_HHMMSS/`: Timestamped folder containing generated reports, charts, and logs.
- `LGProject.ipynb`: Main analysis notebook.
- `requirements.txt`: Python dependencies required for the project.
- `README.md`: Project overview and usage instructions.


┣ 📂 exports_YYYYMMDD_HHMMSS
┃ ┣ 📄 Inventory_By_EAN.xlsx
┃ ┣ 📄 Inventory_By_EAN_Store.xlsx
┃ ┣ 📄 missing_model_or_ean_YYYYMMDD.xlsx
┃ ┣ 📄 top_10_models_chart.png
┃ ┣ 📄 inventory_by_customer.png
┃ ┗ 📄 log_YYYYMMDD.txt
┣ 📄 LGProject.ipynb
┣ 📄 requirements.txt
┗ 📄 README.md
