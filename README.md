Savita Kitchen Sales Analysis

This project combines and analyzes Amazon sales report files (Jan 2022 – May 2026) to find useful business insights.

What this project does--
Combines Data: Merges all monthly CSV sales report files into one file.
Cleans Data: Removes extra columns, checks for null values and duplicates.
Splits Data: Separates orders into Shipment, Cancel, and Refund.
Fixes City Names: Uses India Pincode data to correct messy/duplicate city names.

Analyzes Sales:
Monthly sales trend
Top cities and states by orders
Best-selling products (SKUs)
Monthly trend of top products
Products often bought together
Best hours/times when people order

Files Used-
FilePurposeMonthly sales CSV filesRaw order data (input)all_india_pincode_directory_2025.csvUsed to fix city names using pincodeSales-data-sorted.csvCombined and sorted final data

Tools Used-
Python (pandas, matplotlib, seaborn, plotly)
Jupyter Notebook / Google Colab

How to Run-
Put all monthly CSV files in one folder.
Run the notebook step by step (combine → clean → analyze).
Charts and tables will show sales insights automatically.

Key Insights You Can Get-
Which city/state buys the most
Best-selling products
Sales trend by month and hour
Products customers usually buy together

Notes-
Data has minor null values (~1-2%) due to missing/incorrect pincodes — safely ignored.
City names are standardized using postal code mapping for accuracy.
