# Tesco Financial Statement Analysis, Forecast & Scenario Model

## Project Overview

This project analyses Tesco's historical financial statements and develops an integrated five-year financial forecast for 2026–2030.

The objective was to understand Tesco's historical financial position, identify key financial trends, develop a linked financial model, and analyse how different assumptions and scenarios could affect the company's future performance.

The model is designed to be interactive. Users can change key assumptions and scenario switches to see how the resulting changes flow through the **Income Statement, Cash Flow Statement, Balance Sheet and Output page**.

All monetary values are presented in **£ millions**.

## Data & Methodology

The model uses historical income statement, cash flow statement and balance sheet data for 2024 and 2025. Forecasts from 2026 to 2030 are then generated using a combination of historical trends and forward-looking assumptions.

The main assumptions include:

* Revenue growth
* Inflation
* COGS growth
* Operating expenses
* Working capital
* Capital expenditure
* Depreciation
* Debt and financing
* Interest expense
* Tax
* Dividends
* Cash balances

The purpose of using these assumptions is to create a connected financial model rather than forecasting each financial statement independently.

## Inflation

Inflation is an important driver within the model because changes in the general price level can affect both Tesco's revenues and costs.

For example, higher inflation can increase the cost of goods, operating expenses, capital expenditure and other business costs. Depending on the assumptions, Tesco may also be able to increase selling prices, which affects revenue.

Therefore, inflation can have an indirect effect on:

**Inflation → Revenue/Costs → Profit → Tax → Cash Flow → Retained Earnings → Balance Sheet**

The inflation assumption can also be changed under different scenarios to test how the model responds to different economic conditions.

## Interlinked Financial Statements

One of the main objectives of the project was to ensure that the three financial statements are properly connected.

### Income Statement

The Income Statement calculates revenue, costs, operating profit, interest, tax and ultimately net income.

Net income then feeds into the Cash Flow Statement and Retained Earnings.

### Cash Flow Statement

The Cash Flow Statement explains how the company's cash position changes.

It incorporates:

* Operating cash flow
* Changes in working capital
* Capital expenditure
* Financing activities
* Interest
* Tax
* Dividends
* Debt movements

The resulting ending cash balance feeds directly into the Balance Sheet.

### Balance Sheet

The Balance Sheet reflects the cumulative impact of the other statements.

For example:

* Cash comes from the Cash Flow Statement.
* Fixed assets are affected by capital expenditure and depreciation.
* Debt is affected by financing decisions.
* Retained earnings are affected by net income and dividends.

The model therefore uses the accounting relationship:

**Total Assets = Total Liabilities + Shareholders' Equity**

A balance check is included to ensure that the model remains internally consistent.

## Working Capital

Working capital is also linked to the operating performance of the business.

Changes in items such as:

* Accounts receivable
* Inventory
* Accounts payable

affect both the Balance Sheet and operating cash flow.

For example, an increase in inventory represents an increase in an asset but also uses cash. Therefore:

**Higher Inventory → Lower Operating Cash Flow → Lower Cash Balance**

This demonstrates why the financial statements cannot be analysed independently.

## Capital Expenditure & Depreciation

Capital expenditure affects the model in two ways.

First, it represents a cash outflow in the Cash Flow Statement.

Second, it increases the company's fixed-asset base on the Balance Sheet.

Depreciation then reduces the carrying value of those assets over time and is also recognised as an expense in the Income Statement.

Therefore:

**Capex → Fixed Assets → Depreciation → Profit → Cash Flow → Balance Sheet**

This relationship is incorporated into the forecast.

## Debt, Interest & Dividends

Debt assumptions affect both financing cash flows and the Balance Sheet.

Changes in debt can also affect interest expense, which affects profit before tax and net income.

Dividends have a similar interconnected effect. Dividend payments reduce cash and also reduce retained earnings within shareholders' equity.

Therefore:

**Debt → Interest → Profit → Tax → Cash**

and:

**Net Income → Retained Earnings → Dividends → Cash & Equity**

## Scenario Switches

A key feature of the model is the **scenario-switch system**.

Users can change the model between different scenarios, such as:

* **Base Case**
* **Best Case**
* **Worst Case**

The switches alter the assumptions used by the forecast rather than requiring individual cells to be manually changed.

For example, a scenario can change:

* Revenue growth
* Inflation
* Cost assumptions
* Capital expenditure
* Working-capital assumptions
* Financing assumptions

The effects then flow automatically through the financial statements.

This allows users to investigate questions such as:

> What happens if inflation increases?

> What happens if revenue growth slows?

> How does higher capital expenditure affect cash?

> How does a change in dividends affect shareholders' equity?

The scenario system therefore turns the model into a **dynamic financial analysis tool rather than a static forecast**.

## Output Page

The **Output page** provides a consolidated view of the model's results.

Instead of requiring the user to examine every individual financial statement, the Output page brings the most important indicators together in one place.

The key outputs include measures such as:

* Revenue
* Profitability
* Cash generation
* Cash balance
* Total assets
* Total liabilities
* Shareholders' equity
* Debt
* Key financial ratios
* Forecast trends

The Output page is also designed to respond to the scenario switches.

Therefore, when a user changes the assumptions or selects a different scenario, the outputs update automatically.

This makes the Output page useful for comparing the financial consequences of different assumptions and quickly identifying how the company's financial position changes.

## Key Findings

Under the base assumptions, revenue increases from approximately **£69.9bn in 2025 to £85.7bn in 2030**.

| Metric               |    2025 |     2030 |
| -------------------- | ------: | -------: |
| Revenue              | £69.9bn |  £85.7bn |
| Net Profit           |    £84m |  £7.91bn |
| Total Assets         | £31.6bn |  £44.2bn |
| Shareholders' Equity | £5.24bn | £18.50bn |
| Cash Balance         |   £848m | £13.70bn |

The model therefore produces significant changes in profitability, cash and shareholders' equity under the base-case assumptions.

However, these results are dependent on the assumptions selected. Changing the scenario switches can produce different results.

## Balance Sheet Rectification

During the modelling process, several errors were identified.

The main issues were:

1. Total liabilities and equity had been hardcoded rather than calculated from their components.
2. Shareholders' equity was not consistently linked to common equity and retained earnings.
3. Tax was being deducted twice in the cash-flow calculation.
4. Dividends were not consistently reflected as reductions in retained earnings and cash.
5. The historical balance sheet did not contain sufficient liability information to completely reconstruct the original accounts.

These issues were corrected and the financial statements were re-linked.

An **Other Non-Current Liabilities (Balancing Item)** was introduced where the original dataset did not contain sufficient information to reconstruct the historical liability structure.

After the corrections, **Total Assets equal Total Liabilities and Equity for every forecast year**.

## Conclusion

The project demonstrates how historical financial data can be transformed into an integrated and interactive financial model.

The model combines:

**Historical Data → Assumptions → Inflation & Operating Drivers → Financial Statements → Scenario Switches → Output Page**

The most important feature is that changes to the assumptions flow through the entire model. This allows users to understand not only the forecast result, but also **why the result changes when the underlying assumptions change**.

The model should therefore be viewed as a scenario-analysis tool rather than a guaranteed prediction of Tesco's future performance. Its outputs depend on the assumptions selected by the user.
