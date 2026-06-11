# Customer Behavior Analysis

Hi! This is one of my portfolio projects where I walked through a full customer behavior analysis workflow using Python, SQL, and Power BI.  
The goal was simple: take raw shopping data, turn it into useful insights, and present it in a way that's easy to understand.

## ✨ Features

- End-to-end analysis flow from raw data to dashboard
- Data cleaning and preprocessing in Python
- Business-focused SQL analysis queries
- Interactive Power BI dashboard for storytelling
- Final insights and recommendations for decision-making

## 🧰 Tech Stack

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SQL** (PostgreSQL-style analysis queries)
- **Power BI** (dashboard and visual storytelling)
- **Jupyter Notebook** (analysis workflow)

## 🚀 Project Setup (Run Locally)

1. Clone the repository:
   ```bash
   git clone https://github.com/abhi231210003/Customer_Behavior_analysis.git
   cd Customer_Behavior_analysis
   ```
2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv .venv
   # Windows
   .venv\Scripts\activate
   # macOS/Linux
   source .venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter sqlalchemy psycopg2-binary
   ```
4. Open the notebook:
   ```bash
   jupyter notebook
   ```
5. Run `main.ipynb` step by step and review `customer_behavior_sql_queries.sql` for SQL insights.

## 🔄 Project Workflow

### 1) Data Preprocessing (Python)
- Loaded and explored the customer shopping dataset
- Cleaned data and standardized key columns
- Prepared analysis-ready data for SQL and BI stages

### 2) SQL Analysis
- Wrote analytical queries to answer business questions
- Compared customer segments and spending behavior
- Identified patterns in discounts, subscriptions, and product performance

### 3) Power BI Dashboard
- Built a dashboard to visualize behavior trends
- Focused on KPIs, category performance, and customer insights
- Used visuals to make findings easier to communicate

## 📷 Power BI Dashboard Preview

> I will add my dashboard screenshot here.

![Power BI Dashboard](path/to/dashboard-screenshot.png)

## 📈 Results / Key Insights

Some of the main things I focused on:
- Which customer groups generate the most revenue
- Whether subscribers spend more than non-subscribers
- Which products and categories perform best
- How discounts impact purchase behavior

## 🔮 Improvements / Future Work

- Add deeper cohort and retention analysis
- Introduce RFM segmentation for better customer profiling
- Add forecasting for sales trends
- Publish a cleaner, versioned dashboard snapshot for comparison over time

---

If you're also learning analytics, feel free to fork this project and build on top of it.
