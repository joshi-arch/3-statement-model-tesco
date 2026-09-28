# 3-statement-model-tesco

# Tesco Financial Statement Analysis & Forecast

## Project Overview

This project analyses Tesco's historical financial statements and develops a five-year forecast using a financial modelling approach. The objective was to understand Tesco's financial position, identify trends in profitability and cash generation, and assess how the business could develop under the assumptions used in the model.

All monetary values are presented in **£ millions**.

## Data & Methodology

The model uses historical income statement, cash flow statement and balance sheet data for 2024 and 2025. I then developed forecasts from 2026 to 2030 using assumptions relating to revenue growth, cost of goods sold (COGS), inflation, capital expenditure, debt, dividends and working capital.

Rather than forecasting every line independently, I used relationships between the financial statements. For example:

* Revenue was forecast using assumed annual growth rates.
* COGS was projected using historical cost growth and operating assumptions.
* Depreciation was linked to the asset base and investment assumptions.
* Accounts receivable, inventory and accounts payable were forecast using operating relationships.
* Retained earnings were rolled forward using net profit and dividends.
* Cash flow was used to determine the ending cash balance.
* The balance sheet was checked using **Total Assets = Total Liabilities + Equity**.

## Why I Chose These Assumptions

The assumptions were selected to create a realistic continuation of the historical operating trend while avoiding excessive growth assumptions.

Revenue increases from approximately **£69.9bn in 2025 to £85.7bn in 2030**, representing continued but moderating growth.

COGS increases more slowly than revenue in several forecast periods. This results in an improvement in gross profit and reflects an assumption that Tesco can maintain some operating efficiency as sales increase.

I also assumed continued capital expenditure and gradual debt reduction. Long-term debt falls from **£6.5bn in 2025 to £3.9bn by 2030**, while the model maintains dividend payments.

These assumptions were chosen because they allow the model to reflect three important areas of financial performance: growth, profitability and balance-sheet management.

## Key Findings

The forecast indicates significant improvement in profitability.

| Metric               |    2025 |     2030 |
| -------------------- | ------: | -------: |
| Revenue              | £69.9bn |  £85.7bn |
| Net Profit           |    £84m |  £7.91bn |
| Total Assets         | £31.6bn |  £44.2bn |
| Shareholders' Equity | £5.24bn | £18.50bn |
| Cash Balance         |   £848m | £13.70bn |

Net profit increases substantially from **£84m in 2025 to approximately £7.91bn in 2030**. This is driven mainly by higher revenue, improved gross profit and the assumptions surrounding operating costs.

Shareholders' equity also increases significantly, reaching approximately **£18.5bn by 2030**. This reflects the accumulation of retained earnings despite dividend payments and reductions in common equity.

The cash balance increases from **£848m in 2025 to approximately £13.7bn in 2030**, indicating strong forecast cash generation under the model assumptions.

## Balance Sheet Rectification

During the modelling process, I identified several errors that prevented the statements from being properly linked.

The main issues were:

1. Total liabilities and equity had been hardcoded rather than calculated from their components.
2. Shareholders' equity was not consistently linked to common equity and retained earnings.
3. Tax was being deducted twice in the cash-flow calculation.
4. Dividends were not consistently reflected as a reduction in retained earnings and cash.
5. The historical balance sheet was missing sufficient liability information to reconcile completely.

I corrected these issues and introduced an **Other Non-Current Liabilities (Balancing Item)** where the original dataset did not provide enough information to reconstruct the historical liability structure.

After the corrections, **Total Assets equal Total Liabilities and Equity for every forecast year**, providing an important validation check for the model.

## Conclusion

The model suggests a materially stronger financial position over the forecast period, with increasing revenue, profitability, equity and cash generation alongside declining long-term debt.

However, these results are **model outputs rather than guaranteed outcomes**. They depend heavily on the assumptions used for revenue growth, costs, working capital, capital expenditure, financing and dividends. Therefore, the forecast should be interpreted as a scenario analysis rather than a definitive prediction.

The project demonstrates how the three primary financial statements can be integrated into one model and how accounting errors can be identified through balance-sheet and cash-flow consistency checks.
