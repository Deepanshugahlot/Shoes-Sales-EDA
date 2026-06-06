\# 👟 Shoes Sales — Exploratory Data Analysis (EDA)



!\[Python](https://img.shields.io/badge/Python-3.11-blue?logo=python\&logoColor=white)

!\[Pandas](https://img.shields.io/badge/Pandas-2.0-150458?logo=pandas\&logoColor=white)

!\[Seaborn](https://img.shields.io/badge/Seaborn-0.12-4C72B0)

!\[Status](https://img.shields.io/badge/Status-Complete-brightgreen)



A complete Exploratory Data Analysis on a global shoe sales dataset covering \*\*1,000 transactions\*\*, \*\*6 brands\*\*, \*\*7 countries\*\*, and \*\*3 sales channels\*\*.



\---



\## 📌 Objective



To analyze shoe sales data and extract actionable business insights around:

\- Which brands and shoe types generate the most revenue

\- Which countries and sales channels perform best

\- How price, units sold, and revenue relate to each other

\- Seasonal and monthly revenue trends



\---



\## 📂 Dataset Overview



| Feature | Details |

|---|---|

| \*\*File\*\* | `shoes\_sales\_dataset.csv` |

| \*\*Rows\*\* | 1,000 transactions |

| \*\*Columns\*\* | 10 features |

| \*\*Time Period\*\* | 2024 |



\*\*Columns:\*\* `Sale\_ID`, `Date`, `Brand`, `Shoe\_Type`, `Color`, `Country`, `Sales\_Channel`, `Price\_USD`, `Units\_Sold`, `Revenue\_USD`



\---



\## 🔍 Key Findings



\- \*\*Skechers\*\* had the most transactions (196); \*\*Nike\*\* the fewest (144)

\- \*\*New Balance\*\* and \*\*Adidas\*\* had the highest average revenue per transaction

\- \*\*UAE\*\* was the top market by both transaction volume and average revenue

\- \*\*Sneakers\*\* and \*\*Boots\*\* were the top revenue-generating shoe types

\- \*\*Units Sold\*\* is the strongest driver of revenue (correlation: \*\*+0.73\*\*)

\- Price has low elasticity — customers buy regardless of price point

\- All 3 sales channels (Online, Mall, Retail Store) perform nearly equally (\~33% share each)

\- Only \*\*4 outliers\*\* (0.4%) found in Revenue — clean, high-quality dataset



\---



\## 📊 Analysis Performed



| # | Section |

|---|---|

| 1 | Library Imports \& Setup |

| 2 | Load Dataset \& Inspect Structure |

| 3 | Data Type Conversion |

| 4 | Missing Value Analysis |

| 5 | Duplicate Detection \& Removal |

| 6 | Summary Statistics (Mean, Median, Std, Skewness, Kurtosis) |

| 7 | Univariate Analysis — Distributions \& Count Plots |

| 8 | Outlier Detection — Boxplots \& IQR Method |

| 9 | Bivariate Analysis — Revenue by Brand, Country, Channel, Shoe Type |

| 10 | Correlation Analysis — Heatmap \& Pair Plot |

| 11 | Time Series Analysis — Monthly, Quarterly \& Day-of-Week trends |

| 12 | Key Insights \& Business Recommendations |



\---



\## 🛠️ Tools \& Libraries



\- \*\*Python 3.11\*\*

\- \*\*Pandas\*\* — data manipulation

\- \*\*NumPy\*\* — numerical operations

\- \*\*Matplotlib\*\* — plotting

\- \*\*Seaborn\*\* — statistical visualizations



\---



\## 🚀 How to Run



1\. Clone this repository

&#x20;  ```bash

&#x20;  git clone https://github.com/your-username/shoes-sales-eda.git

&#x20;  cd shoes-sales-eda

&#x20;  ```



2\. Install dependencies

&#x20;  ```bash

&#x20;  pip install pandas numpy matplotlib seaborn jupyter

&#x20;  ```



3\. Launch the notebook

&#x20;  ```bash

&#x20;  jupyter notebook EDA\_Shoes\_Sales\_Deepanshu.ipynb

&#x20;  ```



\---



\## 📁 Repository Structure



```

shoes-sales-eda/

│

├── EDA\_Shoes\_Sales\_Deepanshu.ipynb   # Main analysis notebook

├── shoes\_sales\_dataset.csv           # Dataset

└── README.md                         # Project overview (this file)

```



\---



\## 👤 Author



\*\*Deepanshu\*\*  

Aspiring Data Analyst | Learning Python, Pandas \& EDA  

📬 \[LinkedIn](https://linkedin.com/in/your-profile) · \[GitHub](https://github.com/Deepanshugahlot)



\---





