# Quantitative Risk Modeling & Financial Analytics

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()

This repository contains advanced quantitative risk management and financial data analysis projects developed in Python. The implementations cover core market risk metrics, yield curve modeling, liquidity risk analysis, and credit risk simulations, adhering to rigorous financial engineering frameworks (inspired by John C. Hull and standard industry practices).

---

## 📁 Repository Structure

```text
Quantitative-Risk-Modeling/
│
├── data/
│   ├── phase1/
│   │   ├── DRALACBN.csv             # Historical delinquency and default rate datasets
│   │   └── TEDPIX_Data.csv          # 5-year daily historical returns for TEDPIX index
│   │
│   └── phase2/
│       ├── Treasury_Yields.csv      # 10+ year U.S. Treasury yield curve data (1Y to 30Y)
│       └── Intraday_OrderBook.csv   # Intraday order book snapshot data (Bid-Ask spreads)
│
├── Phase1_Market_Risk_and_VaR.ipynb # Phase I: Market Risk, VaR, EVT, Vasicek & Portfolio Risk
├── Phase1_Market_Risk_and_VaR.html  # HTML Render of Phase I
│
├── Phase2_Credit_Risk_and_PCA.ipynb # Phase II: Advanced VaR, PCA Yield Curves, Liquidity & Credit MC
├── Phase2_Credit_Risk_and_PCA.html  # HTML Render of Phase II
│
├── requirements.txt                 # Required Python libraries
└── README.md                        # Project documentation
