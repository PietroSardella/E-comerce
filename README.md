# 📊 Amazon Sales & Profitability Analysis

This project explores a dataset containing over 3,200 Amazon orders across the United States between 2011 and 2014. Using Python and data visualization tools, we examine category performance, geographic trends, and customer behavior to derive actionable business insights and strategic recommendations.

## 🔍 Project Overview

- **Dataset:** 3,203 Amazon orders with 10 key features (order date, sales, profit, category, geography, etc.)
- **Timeframe:** 2011–2014
- **Tech Stack:** `Python`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

## 🧰 Key Features

### 🧼 Data Cleaning & Exploration
- Handled missing values and ensured data type consistency
- Parsed date fields and split geography into state, city, and country
- Explored value distributions and relationships between sales, profit, and quantity

### 📈 Visual Analytics
- **Sales over time**  
- **Profit vs Sales scatter plots**  
- **Top categories by sales/profit**  
- **Quantity distribution histograms**  
- **State-wise and city-wise performance heatmaps**  
- **Profit margin and average order value by segment**

### 📊 Strategic Business Insights
- Identified top-performing product categories (`Copiers`, `Paper`, `Accessories`)
- Diagnosed underperforming segments and proposed tailored strategies (e.g. bundling, price restructuring)
- Explored customer value distribution and identified high-value segments
- Developed a strategic growth matrix (short-, medium-, and long-term actions)

## 📌 Key Findings

- **California** dominates with over 60% of total sales  
- **Binders** lead in order volume, while **Copiers** offer the highest margins  
- **Machines** and **Bookcases** show net losses and need restructuring  
- **Top 3 cities** (Los Angeles, San Francisco, Seattle) account for ~50% of total revenue  
- **256 high-value customers** contribute disproportionately to profitability

## 🧠 Recommendations

- Discontinue or renegotiate products with persistent negative margins
- Focus marketing and expansion efforts on high-margin categories and cities
- Leverage customer segmentation to increase retention and order frequency

## 📂 File Structure
📁 amazon-sales-analysis/
├── amazon_analysis.ipynb # Main analysis notebook
├── Amazon 2_Raw (1).csv # Original dataset
├── figures/ # Exported charts and graphs
└── README.md # Project documentation


## 📚 Tools & Libraries

- **Python 3.11+**
- `Pandas`, `NumPy` – Data manipulation
- `Matplotlib`, `Seaborn` – Visualization
- `Jupyter Notebook` – Exploratory analysis

## ✨ What I Learned

- Building an end-to-end data storytelling workflow
- Extracting business value from raw transaction data
- Designing targeted, visual reports for strategic decision-making

---

## 🚀 Future Improvements

- Deploy insights to a BI dashboard (Looker Studio or Tableau)
- Build a machine learning model to predict profit margin based on order features
- Create an automated reporting pipeline for monthly sales summaries

---

## 📫 Contact

Made with ❤️ by Pietro Sardella  
Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/pietro-sardella/) or GitHub for feedback or collaboration!


