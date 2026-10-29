# Coca-Cola Sales Analysis (2021)

## Project overview

This project analyses 2021 beverage sales for key American Coca-Cola retailers. The objective is to identify sales patterns across months, regions, brands, retailers, states and cities; compare profitability; and translate findings into practical business recommendations.

**Final deliverable:** `Coca_Cola_Sales_Analysis_Complete.xlsx`  
**Source dataset:** `Coke-sales-analysis-stubs.xlsx`  
**Period covered:** January–December 2021  
**Records analysed:** 3,888 transactions

## Research questions

1. Which months have the highest and lowest sales?
2. How do sales and operating profit differ by region?
3. Which beverage brands generate the highest sales and operating profit?
4. How do brand sales vary across months and regions?
5. How does performance differ across retailers, states and cities?
6. How do price per unit, units sold and operating margin relate to performance?
7. What business actions and follow-up analyses do the results suggest?

## Workbook contents

The completed Excel file contains **13 worksheets**:

| Worksheet | Purpose |
|---|---|
| Dashboard | Summary KPIs and visual overview |
| Analysis Guide | Maps each business question to metrics, visualisations and decisions |
| Monthly Sales | Monthly revenue, profit, units, transaction counts and sales shares |
| Regional Sales | Comparison of five regions |
| Brand Performance | Revenue, profit, units, margin and average unit price across six brands |
| Retailer Performance | Comparison of sales and profitability by retailer |
| Brand Monthly | Month-by-brand revenue comparison |
| Brand Regional | Region-by-brand revenue comparison |
| Geography | State and city performance |
| Price and Margin | Brand-level pricing and profitability comparisons |
| Insights and Actions | Evidence-based findings, possible actions and follow-up checks |
| Data Quality | Validation results, assumptions and limitations |
| Clean Data | Original transaction fields and added time-analysis helper columns |

## Key findings

| Measure | Result |
|---|---:|
| Total sales revenue | $8,684,027.50 |
| Operating profit | $3,173,631.88 |
| Overall operating margin | 36.55% (approximately) |
| Highest-sales month | December 2021 ($1,045,775) |
| Lowest-sales month | March 2021 ($483,530) |
| Leading beverage brand by revenue | Coca-Cola |
| Leading region by revenue | West ($2,835,100) |
| Leading retailer by revenue | Sodapop ($4,403,630) |

These findings are descriptive associations within the supplied 2021 data. They do not, on their own, prove that price, advertising, region or season causes changes in demand.

## Metrics and methods

- **Total sales:** Sum of `Total Sales` for a selected month, region, brand, retailer or location.
- **Operating profit:** Sum of `Operating Profit` for each group.
- **Units sold:** Sum of `Units Sold`.
- **Operating margin:** Total operating profit divided by total sales (revenue-weighted rather than a simple average of transaction margins).
- **Sales share:** Group sales divided by overall sales.
- **Average effective unit price:** Total sales divided by units sold.

The analysis uses aggregation, comparisons, rankings and Excel charts. The visualisation choices follow the provided instructions: line charts for trends; bar charts for category comparison; heatmap-style or comparative views for brand-by-region relationships; and price/volume comparisons for exploratory analysis.

## How to use the Excel workbook

1. Open `Coca_Cola_Sales_Analysis_Complete.xlsx` in **Microsoft Excel**.
2. Start with **Dashboard** for the overall sales picture.
3. Open **Analysis Guide** to see how each requirement is answered.
4. Review **Monthly Sales**, **Regional Sales**, **Brand Performance**, **Retailer Performance**, **Brand Monthly** and **Brand Regional** for detailed comparisons.
5. Use **Geography** and **Price and Margin** for additional analysis.
6. Read **Insights and Actions** for recommended next steps.
7. Check **Data Quality** for validation notes and caveats; inspect **Clean Data** for supporting records.

Excel may recalculate formulas when the file is opened. For best results, use a desktop version of Excel with formula calculation enabled.

## Business recommendations

- Review stock and staffing plans before historically strong months, while verifying the pattern with additional years of data.
- Examine regional performance together with retailer coverage and market size before reallocating budget.
- Evaluate merchandising, distribution and marketing opportunities for leading brands.
- Investigate brands or regions with weaker revenue, distinguishing low unit volume from low effective selling price.
- Assess operating profit and margin alongside sales volume rather than judging success on revenue alone.
- Validate the impact of proposed actions with further data or controlled trials.

## Important limitations

- The dataset covers **one year (2021)**, so recurring seasonal effects cannot be established reliably.
- It contains transaction-level sales and operating profit but not necessarily all business drivers such as promotional activity, competitor prices, stockouts or market population.
- Price-versus-units comparisons are **exploratory** and should not be interpreted as proof of price elasticity or causation.
- Findings apply to the included retailers and recorded transactions, not automatically to the entire US beverage market.

## Submission files

- `Coca_Cola_Sales_Analysis_Complete.xlsx` — completed analysis workbook and dashboard.
- `README.md` — project description, navigation, findings, methodology and limitations.

*Prepared using the supplied Coca-Cola sales dataset and the analysis requirements in the project images.*
