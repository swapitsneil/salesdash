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

<img width="1104" height="760" alt="Image" src="https://github.com/user-attachments/assets/4a0a9500-a14c-4681-9307-88bb907a18bb" />

<img width="2240" height="814" alt="Image" src="https://github.com/user-attachments/assets/10155f1d-2d5a-40f0-adbd-23806099e7f2" />

<img width="1406" height="930" alt="Image" src="https://github.com/user-attachments/assets/afa599ee-3458-4d8f-a5cf-fea12c1063e7" />

<img width="2568" height="966" alt="Image" src="https://github.com/user-attachments/assets/d800ece0-9289-4c14-bdfb-8c40779462d5" />

<img width="2218" height="1002" alt="Image" src="https://github.com/user-attachments/assets/94e94f47-faec-495b-903d-1c33a78171a0" />

<img width="2202" height="806" alt="Image" src="https://github.com/user-attachments/assets/bb9f88e4-d70e-49f7-aeb8-a8654378bafa" />

<img width="2208" height="806" alt="Image" src="https://github.com/user-attachments/assets/5ff9870b-7350-45e3-a709-730a09a8d118" />

<img width="1804" height="1204" alt="Image" src="https://github.com/user-attachments/assets/7689c87f-b21c-468a-a802-772bf0fb8fe2" />

<img width="1382" height="1184" alt="Image" src="https://github.com/user-attachments/assets/3c8644c1-d5a2-451f-b791-ad9dbf39ed8b" />

<img width="1974" height="1156" alt="Image" src="https://github.com/user-attachments/assets/5510dec1-1461-4230-87cd-ee869cb5a639" />

<img width="1062" height="516" alt="Image" src="https://github.com/user-attachments/assets/3dc29baf-0d68-4967-b7e1-2cd59a6dd016" />

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
