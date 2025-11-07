# HF Pairs Trading on NSE — Deliverable Package: 

    This package contains a complete set of deliverables and reference outputs for the high-frequency pairs trading study on NIFTY-50.

## Contents: 

    HF_Pairs_Trading_NSE_Analysis.ipynb - Python Notebook skeleton to explore outputs. 
    
    NSE_PairsTrading_KPIs.xlsx - Excel workbook with summary tabs and breakdowns. 
    
    pair_level_kpis.csv — Pair level KPI distribution (synthetic, shaped per study). 
    
    portfolio_kpis.csv — Portfolio-level scenarios for key comparisons.
    
    charts — PNG images used in the deck/research analysis doc. 
    
   

  ## Repro Notes:
    Data are synthetic placeholders that reflect study structure.
    
    With (10 focal pairs across 7 sectors, 5–60-min bars, 0/1 tick delay, Classical vs Preferred, Ranked vs Random, Carry vs EOD Flat,  rolling cointegration check vs skip).
    
    Update CSVs with your actual backtest results to auto-refresh workbook summaries and charts.
    
    Environment: Python 3.10+, numpy, pandas, matplotlib, python-docx, python-pptx, xlsxwriter.
    
