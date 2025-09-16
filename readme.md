# 📈 Bond Yield Exploration
📌 Overview

This project explores U.S. Treasury yields and spreads using data from the FRED API
.
It starts with a Jupyter Notebook for fetching and visualizing yields, then builds toward a lightweight ETL pipeline and dashboard.

**Goal:** Explore the yield curve and bond spreads using FRED data.

Understand yield curve shapes and spreads (e.g., 10Y–2Y, 10Y–3M).

Learn how yields can signal market conditions and recessions.

Practice data workflows useful in quantitative finance and data engineering.

⚙️ Features

Fetch Treasury yield series from FRED with a simple helper function.

Load into Pandas DataFrames for analysis.

Plot yield curves and spreads across maturities.

Highlight how to calculate Effective Annual Yield (EAY) and other bond metrics.

Extendable to daily ETL jobs and a Streamlit dashboard.
```
bond_yields/
│── notebooks/
│ └── 01_explore_fred.ipynb # Initial data exploration
│
│── src/
│ └── fred_utils.py # Functions to fetch data from FRED
│
│── requirements.txt # Dependencies
│── README.md # Project overview
│── .gitignore # Exclude venv/conda files, secrets
🚀 Getting Started
```
🚀 Getting Started

Clone this repo

git clone https://github.com/yourusername/bond_yields.git
cd bond_yields


Install dependencies

pip install -r requirements.txt


Set your FRED API key

Sign up at FRED

Add it as an environment variable:

export FRED_API_KEY=your_api_key_here


Run the notebook

jupyter notebook notebooks/01_explore_fred.ipynb

📊 Next Steps

Automate daily ETL (fetch → clean → store).

Store data in AWS S3 or a database.

Build a Streamlit dashboard for interactive yield curve analysis.

Add credit spreads, TIPS, or simple backtesting strategies.

📖 Learning Goals

Strengthen finance concepts: bond yields, spreads, recession signals.

Practice Python ETL with APIs.

Build toward quantitative research workflows.