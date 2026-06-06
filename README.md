# 👟 Shoes Sales — Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?logo=pandas\&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-4C72B0)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![EDA](https://img.shields.io/badge/Analysis-EDA-success)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

A complete Exploratory Data Analysis (EDA) of a global shoe sales dataset containing **1,000 transactions**, **6 brands**, **7 countries**, and **3 sales channels**.

---

## 📌 Objective

To analyze shoe sales data and uncover actionable business insights related to:

* Brand performance
* Country-wise sales trends
* Sales channel effectiveness
* Revenue drivers
* Monthly and seasonal sales patterns

---

## 📂 Dataset Overview

| Feature         | Details                   |
| --------------- | ------------------------- |
| **File**        | `shoes_sales_dataset.csv` |
| **Rows**        | 1,000 transactions        |
| **Columns**     | 10 features               |
| **Time Period** | 2024                      |

**Columns:** `Sale_ID`, `Date`, `Brand`, `Shoe_Type`, `Color`, `Country`, `Sales_Channel`, `Price_USD`, `Units_Sold`, `Revenue_USD`

---

## 🔍 Key Findings

* **Skechers** recorded the highest number of transactions (196), while **Nike** recorded the lowest (144).
* **New Balance** and **Adidas** generated the highest average revenue per transaction.
* **UAE** emerged as the top-performing market by both transaction volume and average revenue.
* **Sneakers** and **Boots** were the highest revenue-generating shoe categories.
* **Units Sold** showed the strongest positive relationship with Revenue (**correlation = +0.73**).
* Revenue is influenced by both product pricing and sales volume.
* Sales were relatively balanced across all three sales channels.
* Only **4 revenue outliers (0.4%)** were identified, indicating a clean and reliable dataset.

---

## 📊 Analysis Performed

| #  | Section                                 |
| -- | --------------------------------------- |
| 1  | Library Imports & Setup                 |
| 2  | Load Dataset & Inspect Structure        |
| 3  | Data Type Conversion                    |
| 4  | Missing Value Analysis                  |
| 5  | Duplicate Detection                     |
| 6  | Summary Statistics                      |
| 7  | Univariate Analysis                     |
| 8  | Outlier Detection (IQR Method)          |
| 9  | Bivariate Analysis                      |
| 10 | Correlation Analysis                    |
| 11 | Time Series Analysis                    |
| 12 | Key Insights & Business Recommendations |

---

## 🛠️ Tools & Libraries

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 📈 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Analysis
* Correlation Analysis
* Outlier Detection
* Business Insight Generation
* Pandas & NumPy
* Matplotlib & Seaborn

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/Deepanshugahlot/Shoes-Sales-EDA.git
cd Shoes-Sales-EDA
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch the notebook

```bash
jupyter notebook Shoes_Sales_EDA.ipynb
```

---

## 📁 Repository Structure

```text
Shoes-Sales-EDA/
│
├── Shoes_Sales_EDA.ipynb
├── Shoes_Sales_EDA.pdf
├── shoes_sales_dataset.csv
└── README.md
```

---

## 👤 Author

**Deepanshu Gahlot**

Aspiring Data Analyst. Currently: learning. Always: improving.

📬 [LinkedIn](https://linkedin.com/in/deepanshugahlot001) · [GitHub](https://github.com/deepanshugahlot)

---
