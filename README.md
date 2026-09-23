# Superstore Profitability Analysis

**A data analysis project to identify the root causes of profit loss and provide actionable recommendations.**

---

## 📋 Project Overview

**Stakeholder:** Sarah Jenkins, VP of Sales
**Business Problem:** Despite high sales volume, overall profit margins are not keeping pace. The VP of Sales needs to identify where the company is losing money and how to optimize product and regional strategy.

This project analyzes ~10,000 transactions from the Superstore dataset to uncover the drivers of profitability and the factors eroding margins.

## 🎯 Key Business Questions

1.  Which product categories and sub-categories are the biggest profit drivers, and which are actively losing money?
2.  How do different discount levels affect profitability?
3.  Which regions and states are the most profitable, and which are underperforming?
4.  Which customer segment generates the highest revenue and profit?
5.  Are there specific months or quarters where sales and profits peak or drop significantly?

## 🛠️ Tools & Technologies

*   **Microsoft Excel:** Used for data cleaning, transformation, Pivot Table creation, and custom chart building.
*   **Pivot Tables & Calculated Fields:** To aggregate data and create custom metrics like `Profit Margin %` and `Profit per Unit`.

## 🔍 Data Cleaning & Methodology

*   The dataset was exceptionally clean, requiring minimal cleaning.
*   Data formats were corrected for readability (e.g., currency, percentages).
*   Calculated fields (e.g., `Profit Margin %`) were created within Pivot Tables to provide a deeper, normalized view of performance.
*   Custom Combo Charts were used to visualize multiple metrics (e.g., Total Profit vs. Profit per Unit) simultaneously.

## 💡 Key Insights & Findings

### 1. Product Profitability
*   **Top Profit Driver:** The **Technology** category is the most profitable, led by **Copiers**, which generate an incredible **$237.68 profit per unit**.
*   **Loss Leader:** The **Furniture** category is losing money. **Tables (-$17,725)** and **Bookcases (-$3,472)** are the biggest culprits, losing money on every sale.

### 2. The Discounting Problem
*   Discounting is not universally bad. High-margin items like Copiers remain profitable even with 70%+ discounts.
*   The problem is applying deep discounts to **low-margin products**. For Furniture items like Tables and Bookcases, any discount above 40% pushes them into negative profitability.

### 3. Regional Performance
*   **Top State:** **California** is the highest profit driver at **$76,381**.
*   **Loss Leader:** **Texas** is a major loss leader. Despite high sales volume, it consistently loses money due to aggressive regional discounting.

### 4. Customer Segments
*   The **Consumer** segment generates the most revenue and profit.
*   However, the **Home Office** segment has the **highest profit margin (14%)**, making it a more efficient channel.

### 5. Seasonality & Trends
*   Sales peak dramatically in **November and December** (Thanksgiving, Black Friday, Christmas).
*   However, profit margins are suppressed during this period due to heavy holiday discounting.

## ✅ Recommendations & Conclusion

Based on this analysis, the following actions are recommended:

1.  **Stop Discounting Furniture Immediately:** Tables and Bookcases are destroying value with every discounted sale.
2.  **Double Down on Technology & Home Office:** Focus marketing on high-margin Tech products and the Home Office segment, which has the highest profit per sale.
3.  **Investigate the Texas Market:** Audit pricing and discounting strategies in loss-making states like Texas to stop the financial bleeding.
4.  **Optimize Q4 Strategy:** Shift Q4 focus to high-margin Technology bundles rather than relying on deep discounts that erode profit.

## 📂 Repository Structure

*   `data/`: Contains the raw dataset (`superstore_raw_data.csv`).
*   `analysis/`: Contains the main Excel workbook (`superstore_analysis.xlsx`) with all Pivot Tables and charts.
*   `reports/`: Contains the one-page Executive Summary PDF (`executive_summary.pdf`).
