# 🚚 Logistics Data Analysis

This project showcases end-to-end data analysis on a real logistics network dataset.
It demonstrates the process of:
1. Performing data cleaning, feature engineering, and exploratory analysis in Python to understand shipment-level delay patterns.
2. Converting the cleaned dataset into a SQL database (SQLite) for structured business analysis.
3. Running SQL queries to identify delay hotspots, corridor failures, and operational inefficiencies across the network.

This project highlights skills in data wrangling, SQL analytics, statistical analysis, anomaly detection, and translating findings into business recommendations.

---

## 📂 Repository Structure

| File | Description |
| --- | --- |
| **`notebook.ipynb`** | Complete analysis - cleaning, feature engineering, SQL, visualizations, recommendations |
| **`delhivery.csv`** | Raw dataset (download link below) |

---

## 🛠️ Tech Stack

* **Languages:** Python, SQL (SQLite)
* **Libraries:** pandas, numpy, matplotlib, seaborn, sqlite3
* **Tools:** Jupyter Notebook / Google Colab, Excel, GitHub

---

## 🚀 Getting Started

**1️⃣ Clone the Repository**
```
git clone https://github.com/aditya-01-02/logistics-data-analysis.git
cd logistics-data-analysis
```

**2️⃣ Install Dependencies**
```
pip install pandas numpy matplotlib seaborn
```

**3️⃣ Download the Dataset**

Download the dataset from Kaggle and place it in the project folder as `delhivery.csv`
👉 https://www.kaggle.com/datasets/nayanack/delhivery

**4️⃣ Run the Notebook**
```
jupyter notebook notebook.ipynb
```
> **Google Colab:** Upload `delhivery.csv` directly to the session and run all cells in order.

---

## 📊 Key Insights

*  95.7% of trips exceed their estimated travel time across the network
*  Intra-city last-mile deliveries are the biggest failure point — not long interstate routes
*  Trips dispatched at 7pm are 37% less delayed than trips dispatched at 11am
*  Single-segment trips have the worst delay factor despite having the fewest handoffs
*  Mumbai–Bhiwandi corridor has the highest volume of extreme outlier trips in the network
*  Best performing corridor runs at nearly on-time (factor 0.98) — used as internal benchmark

---

## 🎯 Skills Demonstrated

* Data Cleaning & Feature Engineering (timestamp parsing, city extraction, null handling)
* Trip-level aggregation from segment-level raw data
* SQL Analysis using SQLite
* Statistical Analysis - correlation, percentile-based anomaly detection, distribution analysis
* Data Visualization with Matplotlib & Seaborn (10 charts)
* Business Recommendations with estimated impact from structured estimation
* End-to-End Project Workflow - raw data → cleaning → SQL → insights → recommendations
