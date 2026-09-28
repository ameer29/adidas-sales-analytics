# Adidas: where the growth really is

**A Tableau study of Adidas US sales and profitability by region, product, retailer and channel. It found that the biggest revenue engine isn't where the best margins are, and it ends with an A/B testing plan to validate each recommendation before scaling.**

Marketing analytics · NUS Business School, BMS5504 Marketing Analytics, Visualization & Communication · 2026 · Team of 7

**My role:** I built the Tableau charts and dashboards, led the data analysis, and wrote the A/B testing plan and the conclusion.

[![Full case study](https://img.shields.io/badge/Read-Full%20case%20study-111?style=for-the-badge)](https://ameer29.github.io/adidas-analytics.html)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

---

## The Tableau workbook: 5 dashboards, 15 sheets
| Dashboard | Sheets |
|---|---|
| **Executive Sales Performance** | KPI strip (sales, operating profit, units, margin) · sales by region · operating profit by product · sales by sales method |
| **Profitability & Geographic Insights** | State-level sales map (colour and size = sales) · operating margin by product · sales vs margin bubble chart by product |
| **Product Efficiency & Sales Analysis** | Sales vs units bubble chart (size = operating profit) · profit per unit by product · regional sales + margin combo chart |
| **Sales Trend & Retailer Insights** | Monthly sales trend · sales by retailer |
| **Sales Growth & Trend Analysis** | Sales by channel × year · month-on-month and quarter-on-quarter growth (sheets by teammate Li Yiyue) |

**Calculated fields I wrote:**
- `Profit per Unit = SUM([Operating Profit]) / SUM([Units Sold])`
- `Operating Margin % = SUM([Operating Margin]) / SUM([Total Sales])`
- `Margin Label`, for margin labels on the combo chart

The team's growth sheets use a `YOY Growth` table calculation built with `LOOKUP`.

## Findings
1. **High sales doesn't mean high margin.** The West leads revenue; the South and Midwest have stronger margins at lower volume.
2. **Online is the clearest growth lever.** In-store still dominates, but online grew fastest after COVID.
3. **Retailers are concentrated.** West Gear and Foot Locker lead; Amazon and Walmart are under-used.
4. **Profit leaders depend on the measure.** Men's Street Footwear leads total profit; apparel leads profit per unit.
5. **Demand timing is predictable.** Strong recovery in 2021, and Q3 stayed the peak season even through COVID.

## Test before scaling: the A/B plan
| Test | Group A | Group B | Success metrics |
|---|---|---|---|
| Online growth | Free shipping | 10% discount | Conversion, AOV, units |
| Regional growth | National campaign | South-specific campaign | Sales uplift, operating margin |
| Product positioning | Discount-led apparel | Premium lifestyle apparel | Profit per unit, AOV |
| Retailer activation | Standard listing | Sponsored placement + bundle | Retailer sales, profit |

*These tests are proposed, not run. Historical data shows correlation; experiments show cause.*

## Team
Cecilia Danielli · Chu Chin Yue · Feng Xiaohan · He Qingyan · Li Yiyue · Rick Rowen van der Maas · Ameer Batcha

---
Part of my portfolio · **[ameer29.github.io](https://ameer29.github.io)** · Interactive Tableau Public link coming soon
