# Stock Data Extraction and Visualization

This project demonstrates a practical data science workflow for extracting, cleaning, and visualizing financial data using Python.  
It focuses on **Tesla (TSLA)** and **GameStop (GME)**, combining market price data with company revenue to explore historical trends.

## Overview

The project showcases core data science skills commonly used in real-world analytics tasks:
- Programmatic data extraction from APIs and websites
- Data cleaning and transformation
- Exploratory data analysis
- Interactive data visualization

Stock price data is retrieved via **yfinance**, while revenue data is collected through **web scraping**.

## Data Sources

- **Market data**: Yahoo Finance (via `yfinance`)
- **Revenue data**: Publicly available HTML tables

## Tech Stack

- Python  
- pandas  
- yfinance  
- requests  
- BeautifulSoup (bs4)  
- plotly  
- Jupyter Notebook  

## What This Project Does

- Extracts full historical stock price data for TSLA and GME
- Scrapes and preprocesses quarterly revenue data
- Aligns financial and revenue time series
- Builds reusable visualization functions
- Produces interactive plots comparing stock performance and revenue trends

## Visual Output

The notebook generates interactive charts displaying:
- Historical stock prices
- Quarterly revenue evolution

These visualizations help contextualize market behavior alongside company fundamentals.
