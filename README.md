
# COVID-19 Unemployment Analysis

> How did the pandemic reshape unemployment? This project explores the data.

## Problem
COVID-19 caused one of the fastest rises in unemployment in modern history.
This project digs into the data to understand when, where, and how severely
unemployment spiked — and how recovery looked across regions.

## Dataset
- Source: https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india

## What I Did
- Cleaned and explored the dataset using Pandas
- Analyzed unemployment trends before, during, and after COVID-19 lockdowns
- Built static visualizations (Matplotlib, Seaborn) for trend and distribution analysis
- Built interactive charts using Plotly
- Created an interactive choropleth map to show regional unemployment patterns

## Key Findings
- COVID-19 nearly doubled unemployment rates post-lockdown 
- Urban unemployment is consistently higher than rural
- Haryana, Tripura & Jharkhand are highest unemployment
- Northeast & East zones show structurally higher rates    
- Labour participation & unemployment are positively corr.
## Tools & Libraries
Python | Pandas | Matplotlib | Seaborn | Plotly

## How to Run
pip install -r requirements.txt
jupyter notebook unemployment_analysis.ipynb

## What I Learned
Working with time-series socioeconomic data taught me how much data cleaning
matters before any visualization. The choropleth map also pushed me to learn
Plotly's geo features from scratch.
