# Financial Performance Analysis with SQL: Adventure Works (2017)
Analyzed Adventure Works 2017 financial performance with SQL: gross margin and marketing ROI by country, with an executive summary.

## Objective
Integrate three data sources with SQL queries (sales records, a product catalog with costs, and marketing campaign budgets by territory) to build profitability metrics that can be compared across countries, giving a clear view of global performance.

## Tools
SQL · Spreadsheets · Dashboards

## Dataset
Adventure Works database, reference year 2017: sales records, product catalog with associated costs, and campaign budgets by territory.

## KPIs
| KPI | Formula | Interpretation |
|---|---|---|
| Gross Profit | Revenue - Costs | Profit before marketing spend |
| Gross Margin % | Gross Profit / Revenue | Share of the sale price that remains as profit |
| ROI % | Gross Profit / Campaign Cost | Gross profit generated per dollar invested in marketing |

## Results by Country (2017)
| Country | Revenue | Gross Profit | Margin | ROI |
|---|---|---|---|---|
| United States | $3,353,939.92 | $1,454,468.60 | 43.37% | 75.75% |
| Australia | $2,532,003.49 | $1,057,045.31 | 41.75% | 49.16% |
| United Kingdom | $1,189,636.78 | $508,128.24 | 42.71% | 22.05% |
| Germany | $1,071,460.42 | $460,165.06 | 42.95% | 20.31% |
| France | $924,316.93 | $396,519.79 | 42.90% | 17.96% |
| Canada | $710,205.18 | $317,879.27 | 44.76% | 17.43% |

## Key Findings
1. **United States** is the most profitable market, with a gross profit of **$1,454,468.60** and an ROI of **75.75%**, far ahead of every other territory.
2. Gross margin is stable across countries (**41.8% to 44.8%**), so the difference in performance comes from how marketing is invested, not from the products.
3. **United Kingdom** has the largest campaign budget (**$2.30M**) but only a **22.05%** ROI, so marketing spend there is not generating a proportional return. Canada (17.43%) and France (17.96%) have the lowest ROI.

## Recommendations
- Increasing investment in the United States is the safest short-term move, since its ROI shows the market can absorb more budget and still return more than it costs.
- Review United Kingdom campaigns before maintaining or increasing spend, to find where effectiveness is being lost.
- A 50% budget increase would likely lower ROI unless gross profit grows at the same rate or faster.

## Files
- `sprint_3_-_Proyecto_3__Análisis_del_desempeño_financiero_con_SQL_-_Resumen_ejecutivo.xlsx`: results by country, KPIs, and executive summary.
- `images/`: screenshots of the dashboard and charts.
- [View the Google Sheet](https://docs.google.com/spreadsheets/d/11IcDntSZfmGtCnDdmP_Gz16VL6ASWFFE/edit?usp=sharing&ouid=116118350435914609784&rtpof=true&sd=true)
