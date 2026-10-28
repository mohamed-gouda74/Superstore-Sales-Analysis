# Superstore Sales Analysis 📊

## 📌 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on retail sales data from the Superstore dataset. The objective is to extract actionable business insights regarding sales performance, profitability trends, customer segmentation, geographic profitability, and the impact of discounts on operational margins.

---

## 🛠️ Prerequisites & Libraries
To run the analysis notebook successfully, ensure the following Python libraries are installed:
- numpy
- pandas
- matplotlib
- seaborn

---

## 📂 Dataset Details
- **Total Records (Rows):** 9,994 transactions
- **Features (Columns):** 21 attributes
- **Data Encoding:** `latin1`
- **Key Metrics Included:** Order Date, Ship Date, Customer Segments, Regional Geography, Product Categories, Sales, Quantities, Discounts, and Profit.

---

## 🧹 Data Cleaning & Preprocessing
Data validation steps performed prior to analysis:
1. Converted `'Order Date'` and `'Ship Date'` columns from object type to standard **datetime** format.
2. Verified dataset integrity (`isnull().sum()` confirmed **0 missing values**).
3. Checked for duplicate records (`duplicated().sum()` confirmed **0 duplicate rows**).

---

## 📈 Key Performance Indicators (KPIs)
- **Total Sales:** $2,297,200.86
- **Total Profit:** $286,397.02
- **Total Units Sold:** 37,873 units
- **Average Sales per Order:** $458.61
- **Overall Profit Margin:** 12.47%

---

## 💡 Key Business Insights & Findings

1. **Customer Segments:** 
   - The **Consumer** segment generates the highest sales volume by a large margin, followed by **Corporate** and **Home Office** segments.
2. **Top Customers:** 
   - High-value purchasers such as *Sean Miller* and *Tamara Chand* lead in terms of individual contribution to revenue and profit.
3. **Discount Impact on Profitability:** 
   - There is a notable negative correlation between high **Discounts** and net **Profit** (correlation of approximately -0.22). Discounts exceeding 20% consistently result in severe net operational losses (reaching up to -$6,599.98 in single transactions).
4. **Geographical Performance:** 
   - **California** and **New York** stand out as the most profitable states, with **New York City** driving the highest city-level profit.
5. **Product Sub-Categories:** 
   - While high-demand items like *Phones* and *Copiers* yield strong margins, sub-categories vulnerable to heavy discounting (such as *Tables* and certain *Bookcases*) suffer from negative net profitability.

---

## 🚀 How to Run
1. Clone the repository or download the Jupyter Notebook file.
2. Ensure the `Sample - Superstore.csv` dataset is placed in the correct working directory path.
3. Run all cells sequentially in Jupyter Notebook or JupyterLab.

---

## 👤 Author
**Mohamed Goda**  
*Data Analyst*  
- [GitHub Profile](https://github.com/mohammedgooda22)  
- [Kaggle Profile](https://www.kaggle.com/mohammedgooda22)
