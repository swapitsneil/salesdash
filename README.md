# **SalesDash - Sales Performance Dashboard**
*Python + Power BI Project*

---

## Project Overview

**SalesDash** is a complete **sales performance analysis** project that transforms raw transactional data into **actionable business insights** using **Python (pandas + matplotlib)** and **Power BI**.

This project solves **10 real-world business problems** commonly asked in **data analyst interviews**, including:
- Total revenue & profit
- Category & regional profitability
- Discount impact
- Customer segmentation
- Trend analysis & correlation

---

## Project Structure

```
SalesDash/
│
├── sales.ipynb               → Full Python analysis
├── Dataset
          └── sales.csv       → Dataset
├── SalesDashboard.pbix       → Interactive Power BI dashboard
└── README.md                 → This file
```

---

## Business Problems Solved

| # | Problem | Tool |
|---|-------|------|
| 1 | Overall Business Performance | Python + Power BI |
| 2 | Category Performance | Python + Power BI |
| 3 | Regional Profitability | Python + Power BI |
| 4 | Top 5 Products | Python + Power BI |
| 5 | Monthly Sales Trends | Python + Power BI |
| 6 | Discount Impact on Profit | Python + Power BI |
| 7 | Shipping Mode Efficiency | Python + Power BI |
| 8 | Sub-Category Profit Margins | Python + Power BI |
| 9 | Top 5 Customers | Python + Power BI |
| 10| Quantity vs Profit Correlation | Python + Power BI |

---

## Tools & Technologies

| Tool | Purpose |
|------|--------|
| **Python** | Data cleaning, analysis, visualization |
| **pandas** | Data manipulation |
| **matplotlib / seaborn** | Static charts |
| **Power BI** | Interactive dashboard |
| **DAX** | Dynamic calculations |
| **CSV** | Data source |

---

## Dataset (`sales.csv`)

- **Source**: Inspired by the classic *Superstore* dataset
- **Rows**: ~10,000
- **Key Columns**:
  - `Order ID`, `Order Date`
  - `Sales`, `Profit`, `Quantity`, `Discount`
  - `Category`, `Sub-Category`, `Product Name`
  - `Region`, `Ship Mode`, `Customer Name`

---

## Python Notebook (`sales.ipynb`)

**Beginner-friendly, fully commented code**  
No complex functions, loops, or tricks  
Each problem solved in **separate, readable cells**

### Highlights:
- Clean data loading & type conversion
- Simple `plt.bar()`, `plt.plot()`, `sns.scatterplot()`
- **Business insights** printed after every chart
- Ready to run in **Jupyter Notebook**

> **Run it in 5 minutes** – just open and hit **Run All**

---

## Power BI Dashboard (`SalesDashboard.pbix`)

**Interactive, executive-ready dashboard**

### Key Features:
- **Slicers**: Filter by Region, Category, Year, Segment
- **KPIs**: Total Sales, Profit, Avg Order Value
- **Visuals**:
  - Clustered columns (Sales vs Profit)
  - Line chart with trend line
  - Scatter plot (Discount vs Margin)
  - Treemap, Donut, Top N bars
- **Drill-through**: Click category → see sub-categories
- **Mobile-optimized layout**

> **One-click insights** – perfect for stakeholders

---

## Screenshots

### Power BI Dashboard
![Power BI Dashboard](images/dashboard_preview.png)

### Python Output Example
![Python Charts](images/python_output.png)

---

## How to Run

### 1. **Python Analysis**
```bash
# Install requirements
pip install pandas matplotlib seaborn

# Open notebook
jupyter notebook sales.ipynb
```

### 2. **Power BI Dashboard**
1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Open `SalesDashboard.pbix`
3. Click **Refresh** to load `sales.csv`
4. Explore with slicers!

---

## Business Impact (Sample Insights)

- **Technology** generates **60% of profit** → prioritize inventory
- **Discounts >20%** reduce margin by **45%** → limit deep discounts
- **Top 5 customers** = **40% revenue** → launch VIP program
- **Central region** loses money → audit shipping costs

---

## Why This Project Gets You Hired

| Check | Feature |
|--------|--------|
| **Clean Code** | Beginner-readable Python |
| **Visual Storytelling** | Professional Power BI |
| **End-to-End** | From CSV to dashboard |
| **Business Focus** | Actionable insights |
| **Portfolio Ready** | GitHub + Screenshots |

---

## Author

**Swapnil Nicolson Dadel**  
*Aspiring Data Analyst | Python + Power BI Enthusiast*

---

**Star this repo if you find it helpful!**  
*Built with passion to land your dream data job*
