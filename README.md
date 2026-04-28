# S&P 500 Stock Prices Analysis

A data analysis project combining **Python** and **Power BI** to explore historical stock performance of S&P 500 companies (2014–2017).  
The project focuses on financial metrics, exploratory data analysis, and interactive dashboarding.



## Dataset

- Source: [Maven Analytics S&P 500 Stock Prices Data ](https://mavenanalytics.io/data-playground/s-p-500-stock-prices)
- Description: Historical stock market data for current S&P 500 companies (2014–2017)
- Enhancements:
  - Enriched using `yfinance` Python library
  - Added:
    - Company names
    - Sector classifications



## Tech Stack

- **Python**
  - pandas, numpy
  - matplotlib, seaborn
  - yfinance
- **Power BI**
  - Data modeling
  - DAX calculations
  - Interactive dashboards



## Project Workflow

### 1. Exploratory Data Analysis (Python)

Notebook: `init_data_analysis.ipynb`

- Cleaned and validated raw dataset
- Performed exploratory analysis:
  - Price trends
  - Volatility patterns
- Answered key analytical questions from Maven Analytics



### 2. Feature Engineering

Added financial metrics:

- **Drawdown (%)**
  - Maximum historical decline from peak to trough
    ```
    Drawdown = (Peak - Bottom) / Peak
    ```

- **Total Return (%)**
  - Overall return over the observed period
    ```
    Total Return = (Last Price - First Price) / First Price
    ```



### 3. Power BI Dashboard

Interactive dashboard built to visualize:

- 📈 Stock price trends
- 📉 Drawdowns and total return across companies
- 🏆 Top traded stocks
- 🔎 Filtering by:
  - Stock
  - Time period

![Power BI Dashboard Preview](dashboard/Dashboard%20view.png)

👉 **Click below to explore the interactive Power BI report:**

[![Power BI Dashboard](https://img.shields.io/badge/PowerBI-View%20Dashboard-yellow?logo=powerbi)](https://app.powerbi.com/view?r=eyJrIjoiMTY5OTdmMzktY2ZjOS00ZWU4LTkzZmEtMzlmODE5OGVjZmYxIiwidCI6IjgzMzI4ODBjLTJiZWYtNDMwNC1iMjIzLTkwMmU1NTVlZjMwMSJ9&pageName=2112ce2fd1ca5cabf06a)



## Key Insights

- Technology and healthcare sectors showed strong growth during the period
- Some stocks experienced significant drawdowns despite positive total returns
- Volatility varies greatly across sectors and individual companies

