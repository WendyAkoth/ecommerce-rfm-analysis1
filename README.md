# 🛍️ E-Commerce Customer Analytics & RFM Segmentation

An end-to-end data analytics project exploring customer behavior, sales performance, and retention strategies for an online retail dataset using Python (`pandas`, `seaborn`, `matplotlib`).

---

## 📌 Executive Summary
This project cleans and analyzes transactional data from an online e-commerce platform. Using **RFM (Recency, Frequency, Monetary) Analysis**, customers are segmented into actionable behavioral groups to help drive targeted marketing strategies, boost retention, and maximize customer lifetime value.

---

## 📊 Key Highlights & Insights
* **Revenue Drivers:** Identified top-performing product categories and monthly revenue trends.
* **Customer Segmentation:** Classified the customer base into 4 key tiers (**VIP / Champions**, **Loyal Customers**, **At Risk**, and **Lost**).
* **Business Value:** Mapped out revenue contribution per segment, demonstrating how a small percentage of VIP buyers drive the majority of sales revenue (Pareto Principle).

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Data Processing:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Tools:** Jupyter Notebook, Git, GitHub

---

## 📁 Repository Structure
```text
ecommerce-rfm-analysis/
├── data/
│   ├── raw_online_retail.csv          # Original raw dataset
│   └── cleaned_online_retail.csv      # Processed dataset ready for BI tools
├── notebooks/
│   └── e_commerce_rfm_analysis.ipynb  # Primary Jupyter Notebook with full code & visuals
├── outputs/
│   ├── rfm_segmentation_summary.csv   # Aggregated RFM metrics per customer
│   └── online_retail_with_segments.csv# Combined master dataset
├── README.md                          # Project documentation
└── requirements.txt                   # Python dependencies