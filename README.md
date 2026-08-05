# Retail Profitability Analysis

**Sales are high but margins aren't growing — where exactly is the business losing money?**

BI project that dissects profitability across a global retail network, uncovering which product categories, discount levels, and markets are destroying margin despite strong revenue.

## Key Results

| Metric | Value |
|--------|-------|
| Scope | Global retail transactions |
| Problem Found | Tables & Bookcases show consistent negative margins |
| Discount Threshold | Discounts >20% correlate with negative profitability |
| Seasonal Insight | Year-end sales spikes don't increase profit (aggressive promos) |
| Geo Analysis | Underperforming markets identified via mapping |

## Stack

`Power BI` · `Power Query` · `DAX`

## What I Built

1. **Margin Decomposition** — DAX measures for profit margin %, YoY variation, and category-level P&L
2. **Discount Impact Analysis** — Demonstrated that discounts >20% systematically erode margins
3. **Category Deep-Dive** — Identified Tables and Bookcases as persistent loss-makers requiring price/cost review
4. **Geospatial Mapping** — Located underperforming markets globally
5. **Dashboard UX** — Dark-mode design with divergent conditional formatting (red = loss, green = gain)

## Project Structure

```
├── Dashboard/      # Power BI file (.pbix) + PDF preview
├── Dataset/        # Transaction data (CSV)
├── ETL/            # Excel support files for data quality
└── README.md
```

## Dashboard Preview

[📄 View Dashboard PDF](Dashboard/Dashboard.pdf)
