# Retail Intelligence: From Transactions to Business Decisions

## Project Overview

This project analyzes the Sample Superstore retail dataset to evaluate business performance, identify profitability challenges, and uncover opportunities for improvement.

Using PostgreSQL, Python, and Microsoft Excel, I explored sales trends, product performance, category profitability, and regional differences to translate transactional data into actionable business insights.

## Business Objectives

- Evaluate overall sales and profitability.
- Identify the most and least profitable product categories.
- Investigate loss-making subcategories and products.
- Compare regional profitability.
- Examine the relationship between discounts and product performance.
- Develop business recommendations based on the findings.

## Tools & Technologies

- **PostgreSQL:** Data querying, aggregation, and profitability analysis.
- **Python:** Data analysis and notebook-based exploration.
- **Microsoft Excel:** PivotTables, KPI calculations, and executive dashboard.
- **GitHub:** Project documentation and version control.

## Dataset

The project uses the Sample Superstore dataset, containing 9,994 records and 21 columns.

The dataset includes order dates, customers, product categories, sales, quantities, discounts, profits, and regional information.

The analysis covers 2014–2017.

## Key Performance Indicators

| Metric | Result |
|---|---:|
| Total Records | 9,994 |
| Total Orders | 5,009 |
| Total Sales | $2,297,201.07 |
| Total Profit | $286,397.79 |
| Overall Profit Margin | 12.47% |

## Key Business Findings

### 1. Category Performance

| Category | Sales | Profit | Profit Margin |
|---|---:|---:|---:|
| Technology | $836,154.10 | $145,455.66 | 17.40% |
| Office Supplies | $719,046.99 | $122,490.88 | 17.04% |
| Furniture | $741,999.98 | $18,451.25 | 2.49% |

**Insight:** Furniture generated substantial sales but had significantly lower profitability than Technology and Office Supplies.

### 2. Subcategory Profitability

The three lowest-profit subcategories were:

- Tables: -$17,725.59
- Bookcases: -$3,472.56
- Supplies: -$1,188.99

The strongest profit contributors were Copiers, Phones, and Accessories.

**Insight:** Tables represented the largest subcategory profitability concern.

### 3. Regional Performance

For Tables, Bookcases, and Supplies combined:

| Region | Total Profit | Profit Margin |
|---|---:|---:|
| West | $462.15 | 0.33% |
| South | -$3,281.66 | -5.20% |
| Central | -$6,219.48 | -8.55% |
| East | -$13,348.15 | -14.24% |

**Insight:** The West was the only profitable region across these three subcategories, while the East experienced the largest combined loss.

### 4. Product-Level Analysis

The Lexmark MX611dhe Monochrome Laser Printer generated the largest dollar loss among products analyzed:

- Total sales: $16,829.90
- Total profit: -$4,589.97
- Average discount: 40%

The Eureka Disposable Bags for Sanitaire Vibra Groomer I Upright Vac had the lowest profit margin:

- Total sales: $1.62
- Total profit: -$4.47
- Profit margin: -275.93%

**Insight:** Evaluating both dollar losses and profit margins provides a more complete picture of product performance.

## Business Recommendations

1. **Review Furniture profitability:** Investigate pricing, costs, and discount practices, particularly within Tables.
2. **Prioritize loss-making products:** Review products generating substantial dollar losses and determine whether pricing or product assortment changes are appropriate.
3. **Investigate regional differences:** Examine why the East performs significantly worse than the West across the three loss-making subcategories.
4. **Monitor discount performance:** Evaluate how discount levels are associated with profitability before changing promotional strategies.
5. **Protect profitable categories:** Continue monitoring Technology and Office Supplies as major contributors to overall profit.

These findings identify areas for further investigation; they do not establish that discounts or regional practices caused the losses.

## Project Deliverables

- `sql/` — PostgreSQL queries used for business analysis.
- `python/` — Python analysis notebook.
- `excel/` — Executive sales and profitability dashboard.
- `tableau/` — Reserved for future Tableau visualizations.
- `images/` — Project screenshots and visual evidence.

## Conclusion

This project demonstrates how transactional retail data can be transformed into meaningful business insights through SQL, Python, and Excel.

The analysis identified profitability challenges within Furniture, significant losses in the Tables subcategory, and substantial regional differences.

By combining technical analysis with business interpretation, the project demonstrates a practical approach to data-driven decision-making.