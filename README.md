# Building an AI Financial Analyst with the Assistants API

### Challenge Project 1 - Step 09

A financial analyst project that get finance info from rest api and uses Open AI Assistants API architechture to help end users with financial analysis.

Seed Idea: 
- [Building an AI Financial Analyst with the Assistants API](https://www.mlq.ai/ai-financial-analyst-assistants-api/)

Try it Out For:
1. Getting Financials Comparision
2. Plot Charts to see the Financials Comparision

### Try Prompts

#### 1 - Financials Comparision

Can you compare the financial health of Microsoft and Apple over the last four years, focusing on their balance sheets and key financial ratios?

#### 21 - Financials Comparision And Visual Charts

Evaluate Microsoft vs. Googles's revenue & profitability growth over the past 4 quarters. Visualize the results with one or more charts.

Watch YouTube Video to Understand Code

[<img src="https://img.youtube.com/vi/C14_ghBhlNw/hqdefault.jpg" width="600" height="300"
/>](https://www.youtube.com/embed/C14_ghBhlNw)

### - Assistant Functions

- get_income_statement: Retrieves the income statement data. This function likely fetches detailed revenue, expense, and profit information for a specified entity over a given period.

- get_balance_sheet: Obtains the balance sheet data. This would include assets, liabilities, and shareholder equity details, providing a snapshot of an entity's financial condition at a specific point in time.

- get_cash_flow_statement: Gathers cash flow statement data. It probably details the cash inflows and outflows from operating, investing, and financing activities, offering insights into how an entity generates and uses cash.

- get_key_metrics: Retrieves key financial metrics. This function likely provides important financial indicators that help in assessing a company's financial health, such as EBITDA, return on equity, debt to equity ratio, etc.

- get_financial_ratios: Fetches various financial ratios. These ratios, such as the price-to-earnings ratio, current ratio, or liquidity ratio, are crucial for financial analysis and comparative assessments.

- get_financial_growth: Accesses financial growth data. This function probably tracks the growth trends in various financial aspects like revenue growth, profit growth, etc., over time, indicating the entity's growth trajectory.
