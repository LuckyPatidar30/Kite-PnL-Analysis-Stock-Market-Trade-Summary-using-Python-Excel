# Kite-PnL-Analysis-Stock-Market-Trade-Summary-using-Python-Excel
## Intraday Trading Data Automation using Python & Excel

This project automates the process of analyzing intraday trading data from Kite (Zerodha) order reports. It focuses on MIS (intraday) trades and calculates detailed charges and profit/loss summaries per trade, per stock, and overall performance — all generated into a structured multi-sheet Excel file.

🔍 Problem Statement
The client provided a CSV file containing trading order data with details such as time, type (Buy/Sell), instrument, quantity, price, and order status. The goal was to:

Calculate all trading charges for each trade (brokerage, STT/CTT, GST, SEBI, etc.)

Summarize trades at multiple levels (individual trade, stock-wise, and overall)

Present the output in a user-friendly Excel workbook

📁 Output Structure (Excel Workbook)
Trade-Level Charges – All completed MIS trades with calculated charges

Stock-Wise Summary – Aggregated view by stock and trade type with weighted average price

Overall PnL Summary – Net profit/loss and % charges for each instrument

⚙️ Tech Stack
Python: Data processing and calculations using pandas

ExcelWriter: Exporting multi-sheet Excel files

Financial Concepts: Brokerage rules, STT/CTT, SEBI fees, etc.

✅ Key Features
Ignores rejected trades and handles partially filled & cancelled orders

Supports scaling and generalization for other clients/trading platforms

Helps traders understand their true net returns after all deductions

