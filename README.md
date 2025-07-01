# 📊 Vendor Performance Analytics

## 🚀 Overview

This project analyzes vendor-level performance in a retail/wholesale setting using Python, SQL, and Power BI. It uncovers profitability patterns, inventory inefficiencies, and pricing insights, and delivers actionable strategies to optimize gross profit, reduce slow-moving stock, and diversify vendor reliance.

---

## 🎯 Business Problem

Retailers often struggle with:
- Unsold inventory tying up working capital
- Over-reliance on a small number of vendors
- Poor-performing brands dragging down margins
- Inefficient freight and pricing strategies

This project provides a full-stack analytics solution to address these issues using real data, advanced KPIs, and executive reporting.

---

## 📁 Data Sources

| Table | Description |
|-------|-------------|
| `purchases.csv` | Vendor, brand, quantity, purchase price |
| `sales.csv` | Sales quantity, price, revenue, tax |
| `vendor_invoice.csv` | Freight and delivery costs |
| `purchase_prices.csv` | Actual price tiers and volumes |

---

## 🛠️ Tech Stack

- **Python:** pandas, NumPy, matplotlib, seaborn, scikit-learn
- **SQL:** SQLite (via SQLAlchemy)
- **Dashboards:** Power BI Desktop (`.pbix`)
- **Reports:** PDF + Executive Summary
- **Versioning:** Git, GitHub

---

## 📈 KPIs Computed

- **Gross Profit** = TotalSalesDollars - TotalPurchaseDollars  
- **Profit Margin** = (GrossProfit / SalesDollars) * 100  
- **Stock Turnover** = SalesQuantity / PurchaseQuantity  
- **Sales-to-Purchase Ratio**
- **Freight Efficiency** = Freight / TotalPurchaseQuantity

---

## 🔍 Insights Discovered

- 💰 $2.71M in unsold inventory identified
- 🔥 198 brands had high profit margins but low sales — potential for promotions
- ⚠️ Top 10 vendors contributed 65.7% of purchases — diversification recommended
- 📦 Bulk purchases reduced unit cost by 72%
- 🚚 Freight cost outliers pointed to logistics issues

---

## 📊 Dashboard Preview

> 📍Power BI dashboard includes:
- Vendor summary table with dynamic filters
- KPIs: Profit Margin, Turnover, Gross Profit
- Top Vendors by Profit vs Volume
- Cluster filter (high-performing vs underperforming vendors)
- Unsold inventory drill-downs

![Dashboard Overview](dashboards/vendor_performance.pbix)

---

## 📄 Reports

- 📘 [Download Business Report (PDF)](reports/Vendor Performance Report.pdf)
- 📈 Power BI Dashboard: `vendor_performance.pbix`

---

## 🧠 Strategic Recommendations

- Promote high-margin, low-sales brands using pricing/marketing
- Optimize freight and procurement to reduce operational costs
- Diversify vendor partnerships to reduce supply chain risk
- Implement clearance and demand forecasting for slow inventory
- Use clustering/segment-based actions for vendor prioritization

---

## 📂 Repository Structure

