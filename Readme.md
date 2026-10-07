# Financial Health Dashboard

## Project Overview

The **Financial Health Dashboard** is an interactive financial analytics solution built with **Microsoft Power BI**. The dashboard analyzes an organization's financial performance through **Income Statements, Balance Sheets, and Cash Flow Statements**.

It also provides forecasting capabilities to support **budgeting, financial planning, and data-driven decision-making**, making it practical for **Small and Medium-sized Enterprises (SMEs)**.

## Objectives

* Visualize Income Statements, Balance Sheets, and Cash Flows in a clear and interactive format.
* Analyze profitability and financial performance trends over time.
* Provide forecasting for budgeting and financial planning.
* Monitor key financial KPIs.
* Deliver actionable insights to support decision-makers.

## Tools & Technologies

* **Microsoft Power BI Desktop** — Dashboard development and data visualization
* **Power Query** — Data cleaning and transformation
* **DAX** — Calculated measures, KPIs, and financial calculations
* **Custom JSON Theme (Finance Elite)** — Dashboard styling and visual consistency

## Dataset

The dataset contains financial information covering the following areas:

### Income Statement

* Revenue
* Expenses
* Gross Profit
* Operating Income
* Net Income
* Gross Margin
* Operating Margin
* Net Profit Margin

### Balance Sheet

* Assets
* Current Assets
* Property, Plant & Equipment (PPE)
* Liabilities
* Equity
* Cash

### Cash Flow Statement

* Operating Cash Flow
* Investing Cash Flow
* Financing Cash Flow
* Closing Cash

### Dimensions

* Date Dimension — Year, Month, Quarter
* Company Dimension — Company, Sector

## Dashboard Pages

### 1. Overview

The Overview page provides a high-level summary of the organization's financial health.

#### Key KPIs

* Total Revenue
* Total Assets
* Total Net Income
* Gross Margin

#### Visualizations

* Revenue Distribution by Sector
* Monthly Revenue vs. Net Income Trend

#### Interactive Filters

* Sector
* Year

### 2. Income Statement Analysis

This page focuses on profitability and income statement performance.

#### Key KPIs

* Total Net Income
* Total Revenue
* Total Gross Profit
* Total Operating Income

#### Visualizations

* Total Net Income by Year
* Gross Margin % Trend
* Operating Margin % Trend
* Income Statement Summary Table

#### Interactive Filters

* Sector
* Year
* Company

### 3. Balance Sheet Analysis

This page provides an overview of the organization's financial position, assets, liabilities, and equity.

#### Key KPIs

* Total Equity
* Cash Balance
* Total Assets
* Total Liabilities

#### Visualizations

* Assets, Equity, and Liabilities by Company
* Assets, Equity, and Liabilities Trend
* Total Equity by Year
* PPE vs. Current Assets by Company
* Balance Sheet Summary Table

#### Interactive Filters

* Sector
* Year

### 4. Cash Flow Analysis & Forecast

This page focuses on cash flow performance and future financial expectations.

#### Key KPIs

* Investing Cash Flow
* Operating Cash Flow
* Financing Cash Flow
* Closing Cash
* Forecasted Revenue
* Forecasted Net Income
* Total Revenue
* Total Net Income

#### Visualizations

* Cash Position and Operating Cash Flow Trend with Forecast
* Total Revenue by Year with Forecast

#### Interactive Filters

* Growth Rate

## Key Insights

Based on the dashboard analysis, the following insights were identified:

1. **Revenue Growth:** Revenue increased from **250M in 2020 to 381.85M in 2023**, representing approximately **15% YoY growth**.

2. **Strong Gross Margin:** The Gross Margin reached **45.46%**, indicating strong pricing power and effective cost management.

3. **Net Profitability:** Net Income reached **72.34M**, with a Net Profit Margin of **18.94%**.

4. **Strong Liquidity:** Closing Cash increased from **1.2bn to 1.69bn**, indicating a strong liquidity position.

5. **Low Financial Risk:** Total Liabilities represent only **5.6% of Total Assets**, indicating relatively low financial leverage and financial risk.

6. **Technology Sector Leadership:** The **Technology sector** generated the highest revenue, reaching **381.85M**.

7. **Healthy Core Operations:** Operating Cash Flow reached **84.88M**, confirming strong cash generation from core business operations.

8. **Growing Shareholder Value:** Total Equity increased to **2.45bn**, reflecting a strong equity position.

## Recommendations

Based on the financial analysis, the following recommendations are proposed:

1. **Increase investment in the Technology sector** to capitalize on its strong revenue performance.

2. **Maintain Gross Margin above 45%** through effective cost management and operational efficiency.

3. **Build and maintain cash reserves** to support strategic investments and unexpected financial needs.

4. **Reduce liabilities by approximately 10% annually**, with a target of **130M by 2024**.

5. **Use Power BI forecasting** to support monthly budgeting, financial planning, and resource allocation.

6. **Diversify revenue across different sectors** to reduce concentration risk.

7. **Monitor Operating Cash Flow monthly** and aim to maintain it above **80M**.

8. **Target a Net Profit Margin of 20%** to improve overall profitability.

## Forecasting

The dashboard includes built-in forecasting using **Power BI Analytics** features.

### Forecast Configuration

* **Forecast Length:** 3 years
* **Forecast Period:** 2024–2026
* **Confidence Interval:** 95%
* **Forecasted Metrics:**

  * Total Revenue
  * Operating Cash Flow
  * Closing Cash

The forecasting functionality supports:

* Budget planning
* Financial forecasting
* Cash flow planning
* Revenue planning
* Strategic decision-making

## Data Preparation & Modeling

The project uses **Power Query** for data cleaning and transformation before loading the data into the Power BI data model.

**DAX measures** were created to calculate financial KPIs, profitability metrics, cash flow indicators, and other analytical measures.

A dedicated **Date Dimension** is used to support time-based analysis, including:

* Yearly analysis
* Monthly trends
* Quarterly analysis
* Year-over-year comparisons
* Forecasting

## Deliverables

The project includes the following deliverables:

| File                              | Description                             |
| --------------------------------- | --------------------------------------- |
| `Financial_Health_Dashboard.pbix` | Power BI dashboard and data model       |
| `Financial_Health_Dashboard.pdf`  | PDF export of the dashboard             |
| `Insights_Report.docx`            | Summary of insights and recommendations |
| `theme.json`                      | Custom Finance Elite Power BI theme     |
| `README.md`                       | Project documentation                   |

## Project Structure

```text
Financial-Health-Dashboard/
│
├── Financial_Health_Dashboard.pbix
├── Financial_Health_Dashboard.pdf
├── Insights_Report.docx
├── theme.json
├── FinancialData
└── README.md
```

## How to Use

1. Open `Financial_Health_Dashboard.pbix` using **Microsoft Power BI Desktop**.
2. Navigate through the dashboard pages to explore the financial analysis.
3. Use the available slicers such as **Sector, Year, Company, and Growth Rate** to filter the data.
4. Hover over charts and visuals to view detailed values and tooltips.
5. Review the **Insights_Report.docx** for the main findings and recommendations.
6. Use the PDF version for a quick overview of the completed dashboard.

## Author

**Malak**

**Financial Health Dashboard — Task 1**

**October 2026**

## Notes

* All financial figures are presented in **USD**.
* Revenue, Net Income, and Cash values are expressed in **millions (M)** or **billions (bn)** where applicable.
* The dashboard is optimized for **desktop viewing**.
* The dashboard uses a professional **dark-mode financial theme**.
* The custom **Finance Elite** theme was designed to provide a consistent and professional financial reporting experience.
