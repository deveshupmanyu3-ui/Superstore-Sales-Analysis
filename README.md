# 🛒 Superstore Sales Analysis

## 📋 Business Problem
A US-based retail superstore wants to understand why certain 
products and regions are underperforming despite high sales volume.
The goal is to identify loss-making segments and provide 
data-driven recommendations to improve profitability.

---

## 🛠️ Tools Used
- **Python** — Data cleaning, analysis, visualization
- **Pandas** — Data manipulation
- **Matplotlib & Seaborn** — Charts and graphs
- **SQL (SQLite)** — Business queries and insights
- **Power BI** — Interactive dashboard

---

## 📂 Project Structure
Superstore-Sales-Analysis/
│
├── Superstore_Sales_Analysis.ipynb  # Python analysis notebook
├── SQL_DATABASE.ipynb               # SQL queries notebook
├── superstore_cleaned.csv           # Cleaned dataset
├── superstore.db                    # SQLite database
├── superstore sales analysis.pbix   # Power BI dashboard
├── dashboard_preview.png            # Dashboard screenshot
├── sales_by_region.png              # Sales by region chart
├── profit_by_category.png           # Profit by category chart
├── profit_by_subcategory.png        # Profit by sub-category chart
├── monthly_sales_trend.png          # Monthly sales trend chart
├── discount_vs_profit.png           # Discount vs profit chart
└── README.md

---

## 🔍 Key Findings

### 1. Regional Performance
- West region leads in both sales and profit
- Central region has lowest profit despite decent sales
- All regions show consistent growth year on year

### 2. Category Analysis
- Technology is most profitable category
- Furniture has lowest profit margin
- Office Supplies shows stable consistent returns

### 3. Product Level Losses
- Tables sub-category making a loss of $17,000+
- Bookcases and Supplies also underperforming
- Copiers are the highest profit generating product

### 4. Discount Impact
- Clear negative correlation between discount and profit
- Orders with 40%+ discount almost always result in losses
- Excessive discounting is primary cause of losses

### 5. Sales Trends
- Business growing consistently from 2014 to 2017
- 2017 recorded highest orders and revenue
- November and December consistently peak sales months

---

## 💡 Business Recommendations

**Recommendation 1 — Fix Furniture Losses**
> Reprice or discontinue Tables and Bookcases.
> Eliminating heavy discounts on these products alone
> could recover $17,000+ in annual losses.

**Recommendation 2 — Control Discounting**
> Cap maximum discount at 20% across all categories.
> Data shows any discount above 30% results in losses.
> This single policy change could significantly improve margins.

**Recommendation 3 — Invest in Copiers**
> Copiers generate the highest profit among all products.
> Increasing marketing and inventory for Copiers could
> maximize returns with minimal risk.

**Recommendation 4 — Seasonal Strategy**
> November and December show consistent sales spikes.
> Increase inventory and marketing budget from October
> to fully capitalize on peak season demand.

---

## 📊 Dashboard Preview

<img width="1159" height="656" alt="Screenshot 2026-05-29 114113" src="https://github.com/user-attachments/assets/818c324d-52c0-4727-bdce-e92ce7e392a2" />

---

## 📈 Dataset
- **Source:** Kaggle — Superstore Sales Dataset
- **Records:** 9,994 orders
- **Period:** 2014 — 2017
- **Region:** United States

---

## 👤 Author
**DEVESH UPMANYU**
- LinkedIn: www.linkedin.com/in/devesh-upmanyu
- Email: dsprince1604@gmail.com
