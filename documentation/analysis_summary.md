# Analysis Summary — New-Peth Shoes

## 1. Business context

New-Peth Shoes Ltd. was presented in the MSc assignment as an online footwear retailer. The task was to assess whether growth was profitable and which products, customer segments, fulfilment choices and returns patterns warranted management attention.

## 2. Data and tools

- **Input:** sales dataset provided for the university module (not publicly redistributed here).
- **Data preparation:** Microsoft Excel.
- **Business intelligence and visualisation:** Tableau.
- **Output:** executive dashboard, supporting views and a written interpretation with recommended actions.

The source files and executable Tableau workbook are not available in this public portfolio at present. Reported methodology is based on the submitted project write-up.

## 3. Data preparation documented in the assignment

1. Reviewed missing and blank categorical fields, including household type, without discarding important sales records unnecessarily.
2. Standardised regional categories to make geographic aggregation comparable (for example, inconsistent labels for the South East).
3. Removed exact duplicate rows while retaining repeated order identifiers when they represented multiple line items within an order.
4. Validated numeric fields such as sales, discounts and profit; retained plausible negative profits caused by discounts or returns.
5. Created Tableau calculated fields for measures such as profit margin, return rate and expected versus actual shipping time.

## 4. Headline KPIs

| Measure | Reported result |
|---|---:|
| Revenue/sales | £529K |
| Profit | £112K |
| Profit margin | 21.17% |
| Orders | 775 |
| Distinct customers | 529 |

Figures relate to the educational dataset and have not been recalculated independently from raw records.

## 5. Analysis findings

### Category and household performance

The report identifies stronger performance from some women's-shoe product lines and notes that family households contributed prominently to sales and profit. High sales volume alone did not consistently correspond to the strongest margin.

**Decision implication:** Review high- and low-margin sub-categories separately when setting inventory and promotional priorities.

### Sales and profit over time

Sales and profit did not move proportionately in every period. The analysis discusses discounting, fulfilment and returns as plausible pressures, but the dashboard does not prove they caused a particular change.

**Decision implication:** Add margin and discount-rate checks to growth reporting rather than optimising solely for revenue.

### Shipping and delivery

The project reviewed shipping-mode performance, late/pending statuses and variation across regions. Standard delivery accounted for much of the activity, while the project discussed whether express delivery may offer additional margin opportunities.

**Decision implication:** Investigate where fulfilment issues are concentrated; test delivery propositions before rolling them out.

### Returns

Returns appeared unevenly distributed across categories, potentially linked to fit, product expectations and product-information quality.

**Decision implication:** Review category-specific return rates, product descriptions and sizing information.

## 6. Recommended management actions

| Priority | Recommendation | Suggested monitoring KPI |
|---|---|---|
| 1 | Invest selectively in profitable categories, not just high-volume products | Gross/operating profit margin by sub-category |
| 2 | Track discounting and returns alongside sales growth | Margin trend, discount rate, return rate |
| 3 | Assess delivery performance by shipping mode and region | On-time delivery, delayed orders, cost/order |
| 4 | Improve sizing, description and expectation-setting in return-prone lines | Return rate and net margin by product |
| 5 | Target high-value customer segments with relevant campaigns | Repeat-purchase rate, revenue/customer |

These are **recommendations based on the analysis**, not documented interventions or measured improvement after implementation.

## 7. Limitations

- The underlying data are an educational dataset, not disclosed live company transactions.
- Screenshots document the work, but the absent Tableau workbook prevents direct inspection of calculations and filters.
- Aggregate patterns do not by themselves establish causal mechanisms.
- Changes in future performance cannot be quantified without intervention testing or further data.

## 8. Portfolio presentation

Use the four screenshots in the repository's `images/` folder as visual evidence. For an interview, explain the sequence: **business question → data quality checks → KPIs → dashboard → commercial interpretation → recommendation**.
