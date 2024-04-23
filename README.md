# WARREN BUFFET'S ANALYZER

## Table of contents
- [Project Overview](#project-overview)
- [Data source](#Data-source)
- [Analysis Tools used](#Analysis-Tools-used)
- [Methodology](#project-methodology)
- [Results and findings](#results-and-findings)
- [Limitations](#limitations)
- [Conclusion](#conclusion)
## Project Overview
Following the principles outlined in the book "Warren Buffett and the Interpretation of Financial Statements", this project analyzes the  "Apollo Hospitals Enterprise Ltd" company's financial statements using a custom Excel model. Key metrics are then visualized in Power BI dashboards, replicating Buffett's value investing approach. This allows for faster and more efficient identification of companies with strong financial health and long-term potential.

## Data source
The financial data is retrieved from screener.io (https://www.screener.in/company/APOLLOHOSP/consolidated/#balance-sheet)

## Analysis Tools used:
- MS excel
- MS Power BI

## Project Methodology
### Data cleaning/preparation - excel
  - The financial data was imported to excel. Seperate spreadsheets were created for income statements, Balance sheet and Cash flow statements.
  - The column width was adjusted and the spellings were checked.
### Data exploration/analysis - excel
  - A seperate spreadsheet called analyzer was created in which several values were calculated and compared with the rules given in the book to find out whether the company has a competitive edge.
  - The cells were formatted based on the given conditions where red, orange and green signifies bad, moderate and good respectively.
    
    <img width="656" alt="WB_analyzer_excel" src="https://github.com/Guruprasad712/guruportfolio.github.io/assets/160844022/d23f0813-cb3d-46e5-acf9-083e30dd4f1a">

### Data visualization - Power BI
  - The data in the analyzer sheet was exported to Power BI for visualization.
  - The data was cleaned and then loaded.
  - Seperate pages were created for visualizing income statements, Balance sheet and cash flow statements.
## Results and findings
### Income statements
  - The Gross Profit margin and the SA margin(selling and admin) are moderate
  - The Interest margin and Net earnings are bad
  - The Depriciation margin showed a steady increase until 2021 after which it decreased.

    <img width="698" alt="income_statement" src="https://github.com/Guruprasad712/guruportfolio.github.io/assets/160844022/76668d37-52ae-441d-bd58-0f75a9c4d818">

### Cash flow statements
  - Both the net cash flow and the cash from the investing activity graphs shows a fluctuating pattern

    <img width="701" alt="cash_flow" src="https://github.com/Guruprasad712/guruportfolio.github.io/assets/160844022/c3d3bb24-65c9-4f03-a96b-b0673c942126">

### Balance sheet
  - Net worth, Gross tangible assets and investments graphs shows a steady increase.
  - The solvency ratio is above 1
  - The return on assets graph shows a fluctuating pattern.

    <img width="699" alt="balance_sheet" src="https://github.com/Guruprasad712/guruportfolio.github.io/assets/160844022/1861186b-cc7c-4acd-a348-382ebe440d25">

## Limitations
  - To analyze the financial situation of other companies, The data can only be imported from screener.io
  - Domain knowledge is required to interpret certain values.
## Conclusion
#### This analysis of Apollo Hospitals Enterprises Ltd.'s financial data reveals moderate performance, possibly influenced by the competitive nature of the healthcare industry.To get more accurate details on the performance, Other companies in the healthcare sector need to be analyzed.
    
    
