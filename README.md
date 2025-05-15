# Retail Purchase Pattern Mining

This project analyzes customer purchasing behavior using **Association Rule Mining** techniques to support retail optimization. It was developed as part of a data analytics academic submission.

---

## **Problem Statement**

Retail businesses often struggle to identify hidden purchasing patterns, which leads to missed cross-sell opportunities and suboptimal inventory placement. This project uncovers frequent itemsets and product associations using historical transaction data.

---

## **Dataset**

- **File Name**: `Customer_Transactions.xlsx`
- **Size**: 20 sample transaction records
- **Features**: Transaction ID, Product Name, Quantity, Price, Payment Mode, Season, Promotion, etc.
- **Source**: Manually prepared for academic demonstration

---

## **Technologies Used**

- Python (Jupyter Notebook)
- Libraries: pandas, matplotlib, seaborn, mlxtend
- Tools: Excel, GitHub, MS Word

---

## **Approach**

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Frequent Itemset Mining (Apriori)
4. Association Rule Generation
5. Visualizations of product frequency and rule strength

---

## **Key Findings**

- “Milk & Bread” were purchased together in over 22% of transactions.
- Items like **Coffee, Cheese, and Butter** showed strong lift scores.
- Weekday transactions were higher, especially mid-morning.
- Promotions had visible influence on higher quantity purchases.

---

## **Visuals**

**Top 10 Most Purchased Products:**

![Top 10 Products](visualizations/top_10_products.png)

---

## **Recommendations**

- Bundle high-lift items for promotions
- Prioritize cross-sell at checkout (e.g., Milk + Bread)
- Reorganize shelf layout based on frequently bought-together items
- Integrate real-time rule mining in POS systems for dynamic recommendations

---

## **Folder Structure**

```
Retail_Purchase_Analysis/
├── data/
│   └── Customer_Transactions.xlsx
├── notebooks/
│   └── Association_Rule_Mining.ipynb
├── report/
│   └── Phase-3_Submission_Final.docx
├── visualizations/
│   └── top_10_products.png
├── README.md
```

---

## **Author**

- [Your Name]
- [Your Institution]
- Submitted: May 2025
