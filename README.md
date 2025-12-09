# NVIDIA (NVDA) DCF Valuation Model

This project implements a full **Discounted Cash Flow (DCF)** valuation for **NVIDIA (NVDA)** using **Python + Excel**.

## 📌 Features

- Pulls historical financial data (Income Statement, Cash Flow, Balance Sheet)
- Builds a clean historical Free Cash Flow (FCF) table
- Forecasts revenue, EBIT, D&A, CapEx, and FCF for 5 years
- Computes:
  - Enterprise value using **Gordon Growth method**
  - Enterprise value using **Exit EBITDA multiple**
- Calculates equity value and value per share
- Exports a fully formatted **Excel model** (Assumptions, Historical, Forecast, DCF sheets)
## 🧱 Files

- `NVDA_DCF.ipynb` – main Jupyter notebook with all steps
- `dcf_engine.py` – (optional) Python module with reusable DCF logic
- `NVDA_DCF_AI2_op.xlsx` – final Excel valuation model
- `screenshot_assumptions.png` – assumptions sheet
- `screenshot_dcf.png` – DCF valuation sheet
- `screenshot_forecast.png` – forecast sheet

## 🛠 Tech Stack

- Python (pandas, numpy, yfinance, xlsxwriter)
- Excel
- Jupyter Notebook

## 🚀 How to Run

1. Clone the repo:
   ```bash
 git clone https://github.com/omkarmandve2123-debug/Equity_DCF_Engine.git
cd Equity_DCF_Engine
