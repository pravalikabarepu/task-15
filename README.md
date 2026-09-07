# Superstore Profit Margin Analysis

## 📌 Project Overview

This project analyzes the **profitability of the Superstore dataset** using Microsoft Power BI. The analysis focuses on profit margins across **products, categories, regions, and months** to move beyond revenue analysis and identify areas that contribute positively or negatively to profitability.

## 🎯 Objective

* Analyze profit margin by product, region, category, and month.
* Identify products with negative profit margins.
* Compare regional and category-level profitability.
* Track monthly changes in profit margin.
* Support data-driven pricing and cost decisions.

## 🛠️ Tools Used

* **Microsoft Power BI**
* **DAX**
* **Superstore Dataset**

## 📊 Key Metrics

* **Total Sales:** 2.30M
* **Total Profit:** 286.40K
* **Overall Profit Margin:** 12.47%
* **Negative Margin Products:** 299

### Profit Margin Calculation

```DAX
Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)
```

## 📈 Dashboard Visuals

1. **Margin by Product** – Bottom 10 products based on profit margin.
2. **Margin by Category** – Compares profitability across product categories.
3. **Margin by Region** – Compares profit margins across regions.
4. **Sales vs Profit** – Shows the relationship between sales and profit.
5. **Monthly Profit Margin Trend** – Tracks profitability changes over time.

### Filters

* Order Date
* Category
* Region
* Segment

## 🔍 Key Insights

1. The business generates **2.30M in sales and 286.40K in profit**, resulting in an overall profit margin of **12.47%**.
2. **West region** has the strongest profit margin among the regions.
3. **Technology and Office Supplies** have stronger margins than Furniture.
4. Several products have **negative profit margins**, indicating potential pricing, discount, or cost issues.
5. Monthly profit margins fluctuate throughout the year, highlighting changes in profitability over time.

## 💡 Business Recommendations

* Review products with consistently negative margins.
* Investigate excessive discounts and pricing strategies.
* Focus on high-margin categories and products.
* Analyze regional differences to improve profitability.
* Monitor monthly margin trends to identify periods of declining profitability.

