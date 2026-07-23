# 🪔 Diwali Sales Analysis

An exploratory data analysis (EDA) project that uncovers customer purchasing patterns during the Diwali sales season using Python, Pandas, and Seaborn.

## 📌 Overview

This project analyzes a retail dataset of Diwali sales transactions to understand **who is buying, what they're buying, and where they're buying from**. The goal is to help a business identify its core customer segments and optimize marketing and inventory strategy for future festive-season sales.

## 📊 Dataset

The analysis uses `Diwali Sales Data.csv`, which contains transaction-level records with the following key attributes:

| Column | Description |
|---|---|
| `User_ID` | Unique customer identifier |
| `Gender` | Customer gender |
| `Age` / `Age Group` | Customer age and age bracket |
| `Marital_Status` | Married / unmarried |
| `State` | Customer's state of residence |
| `Occupation` | Customer's profession |
| `Product_Category` | Category of purchased product |
| `Product_ID` | Unique product identifier |
| `Orders` | Number of orders placed |
| `Amount` | Purchase amount (₹) |

> **Note:** The raw CSV file is not included in this repository. Place `Diwali Sales Data.csv` in the project root before running the notebook.

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** – data cleaning and aggregation
- **NumPy** – numerical operations
- **Matplotlib** & **Seaborn** – data visualization
- **Jupyter Notebook** – interactive analysis environment

## 🔍 Analysis Workflow

1. **Data Loading & Cleaning**
   - Load CSV with proper encoding handling (`unicode_escape`)
   - Drop irrelevant/unnamed columns
   - Handle missing values
   - Fix data types (e.g., cast `Amount` to integer)

2. **Exploratory Data Analysis**
   - Gender-wise purchase distribution
   - Age group analysis by gender
   - Sales by age group
   - Top 10 states by order volume and revenue
   - Marital status vs. spending behavior
   - Occupation-wise purchasing trends
   - Product category performance
   - Top 10 best-selling products

## 💡 Key Findings

- **Gender:** Female customers make up the majority of buyers and also show higher purchasing power than male customers.
- **State:** Uttar Pradesh, Maharashtra, and Karnataka generate the highest order volumes and revenue.
- **Marital Status:** Married customers — particularly married women — account for the highest spending.
- **Occupation:** Buyers working in **IT, Aviation, and Healthcare** sectors contribute the most to sales.
- **Product Category:** **Food, Clothing, and Electronics** are the top-performing product categories.

### 🎯 Target Customer Profile

> **Married women, aged 26–35, based in Uttar Pradesh or Maharashtra, working in IT, Healthcare, or Aviation — most likely to purchase Food, Clothing, and Electronics.**

## 🚀 Getting Started

### Prerequisites

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### Running the Notebook

1. Clone or download this repository
2. Place `Diwali Sales Data.csv` in the same directory as the notebook
3. Launch Jupyter Notebook:

```bash
jupyter notebook Diwali_Sales_Analysis.ipynb
```

4. Run all cells sequentially

## 📁 Project Structure

```
├── Diwali_Sales_Analysis.ipynb   # Main analysis notebook
├── Diwali Sales Data.csv         # Raw dataset (not included)
└── README.md                     # Project documentation
```

## 📈 Future Improvements

- Add a predictive model to forecast sales for upcoming festive seasons
- Build an interactive dashboard (Power BI / Tableau / Streamlit)
- Perform cohort or RFM (Recency, Frequency, Monetary) analysis
- Deploy insights as an automated reporting pipeline

## 📄 License

This project is intended for educational and portfolio purposes.
