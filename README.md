# Business Performance Dashboard — Superstore Analysis

## 📋 Business Problem
A retail business needed to identify profit leakage 
and revenue growth opportunities across regions, 
categories and customer segments — and understand 
return patterns and regional manager accountability 
to support executive decision making.

## 📊 Dashboards
Two interactive dashboards with navigation:

### Dashboard 1 — Business Overview
https://public.tableau.com/app/profile/lavanya.prathipati/viz/BusinessPerformanceDashboardSuperstoreAnalysis/ReturnAnalysis?publish=yes

<img width="1919" height="1079" alt="Business Analysis Dashboard" src="https://github.com/user-attachments/assets/e8adc227-1a2e-4733-98bb-0fd6923696e8" />


### Dashboard 2 — Returns & Manager Analysis
<img width="1919" height="1079" alt="Return Analysis" src="https://github.com/user-attachments/assets/88a1b25e-4851-41d4-a84d-233742b97e47" />


## 🔍 Key Findings

### Business Overview
- **Central region** has lowest profit margin at 7.9% 
  vs company average 12.56% — driven by average 
  discount of 24.1% vs company avg 15.5%
- **Tables subcategory** generates -$17,753 profit 
  on $208,020 sales — selling at a loss
- **Revenue grew 53%** from $0.49M (2023) to 
  $0.75M (2026) but profit margin remains thin
- **Consumer segment** drives 50% of total revenue 
  at $1.17M

### Returns Analysis
- **296 returns** wipe out 8.1% of total profit 
  ($23.23K of $286K) — disproportionate impact
- **West region** has highest return rate at 11.56% 
  — separate root cause from Central discount issue
- **Technology** has highest return rate at 7.88% 
  across all categories
- **Roxanne Rodriguez** (Central region manager) 
  has lowest profit at $39.8K with highest discount 
  rate of 24.1%
- No single customer dominates returns — issue is 
  at product/category level not customer level

## 🛠️ Tools & Techniques
- Tableau Public
- Joined 3 data tables: Orders + Returns + People
- Dynamic conditional coloring using WINDOW_MIN
- LOD expressions for benchmark comparisons
- Calculated fields: Profit Margin %, Return Rate %, 
  Profit Lost to Returns
- Navigation between two dashboards
- Tooltip customisation

## 📁 Dataset
- **Orders** — sales, profit, discount, shipping data
- **Returns** — order return status
- **People** — regional manager mapping

## 💡 Skills Demonstrated
- Multi-table data joins
- Advanced calculated fields
- Dynamic coloring based on performance thresholds
- Executive dashboard design
- Data-backed insight generation
- Cross-dashboard navigation
