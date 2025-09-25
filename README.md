# Margin and Stock Risk Analysis

## Overview
This project focuses on analyzing product performance from three perspectives:  
1. **Profit Margin**  
2. **Stock Risk**  
3. **Day of Inventory (DOI)**  

The goal is to provide actionable insights into **profitability, inventory efficiency, and sales velocity** to support better decision-making in pricing, stocking, and sales strategies.

---

## 1. Margin Analysis
Products are classified based on their **profit margin (%)**:

- **High Margin**: `margin ≥ 40%`  
- **Medium Margin**: `20% ≤ margin < 40%`  
- **Low Margin**: `margin < 20%`

📊 *Finding:*  
The profit margin distribution is **non-normal**, with peaks around **10%**, **20–25%**, and **50%**, and smaller clusters near **30–35%** and **60–70%**.  
This suggests that the company has **different product groups with varying levels of profitability**.

---

## 2. Stock Risk Analysis
Products are classified by comparing **stock availability** and **units sold**:

- **Overstocked**: Stock above Q3 but sales below Q1 (risk of excess inventory).  
- **Lowerstocked**: Stock above Q3 and sales above Q3 (risk of shortage if not replenished).  
- **Normal**: Products outside these extremes, considered balanced.

📊 *Finding:*  
The classification highlights potential risks of **holding costs** (overstocked) and **lost sales** (lowerstocked).

---

## 3. Day of Inventory (DOI) Analysis
Products are segmented by **sales velocity (days of inventory)**:

- **Unsold**: No sales recorded.  
- **Fast-Selling**: `DOI ≤ 30 days` → high demand.  
- **Normal-Selling**: `31 ≤ DOI ≤ 90 days` → healthy turnover.  
- **Slow-Selling**: `DOI > 90 days` → low demand or stagnant stock.

📊 *Finding:*  
DOI classification reveals which products move quickly, which need monitoring, and which require clearance or marketing actions.

---

## Recommendations
1. **Margin Strategy**
   - Prioritize **High Margin** products for profitability.  
   - Reassess pricing and costs for **Low Margin** items.  
   - Monitor **Medium Margin** products for improvement opportunities.

2. **Stock Risk Management**
   - **Overstocked**: Apply discounts, bundling, or promotions to reduce inventory.  
   - **Lowerstocked**: Replenish quickly to avoid stockouts.  
   - **Normal Stock**: Maintain current strategy.

3. **Sales Velocity (DOI) Actions**
   - **Unsold**: Review product-market fit or consider phase-out.  
   - **Fast-Selling**: Ensure sufficient supply and monitor pricing opportunities.  
   - **Normal-Selling**: Continue current policy.  
   - **Slow-Selling**: Use marketing, repositioning, or clearance actions.

---

## Conclusion
By integrating **Margin Analysis, Stock Risk, and DOI**, this project provides a **comprehensive view of profitability, inventory health, and sales velocity**.  
The combined insights support better business strategies to **minimize risks, reduce costs, and maximize profitability**.
