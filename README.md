# Stock Market Data Analysis

Analyzing stock price trends, returns, and volatility using Python, pandas, and matplotlib.

## 📌 Project Overview

This project analyzes historical stock data for three companies — **TCS**, **INFY**, and **RELIANCE** — over a 2-year period (2023-2024). It covers data collection, cleaning, calculation of key financial metrics, visualization, and written analysis of the findings.

This was built as a hands-on learning project to understand pandas, data visualization, and basic financial analysis concepts.

## 🛠️ Tools Used

- **Python**
- **pandas** — data manipulation and analysis
- **matplotlib** — data visualization
- **yfinance** — fetching historical stock market data
- **Google Colab** — development environment

## 📊 What This Project Does

- Pulls 2 years of historical stock data (Open, High, Low, Close, Volume) for TCS, INFY, and RELIANCE using yfinance
- Cleans and prepares the data (handles missing values, fixes column structure)
- Calculates 7-day and 30-day moving averages
- Calculates daily returns and 7-day rolling volatility
- Compares stock performance using normalized growth (base=100) for a fair comparison
- Visualizes closing price trends, moving averages, and volatility across all 3 stocks

## 🔑 Key Findings

- **TCS** delivered the strongest and most consistent growth with moderate volatility (Avg Return: 0.068%, Avg Volatility: 1.15%)
- **INFY** had nearly identical average returns to TCS (0.068%) but the highest volatility of the three (1.30%), meaning similar reward with more risk
- **RELIANCE** was the most stable in terms of volatility (1.17%) but had the lowest average returns (0.013%)

## 📈 Charts
   <img width="1920" height="866" alt="Screenshot 2026-08-24 144224" src="https://github.com/user-attachments/assets/5ef5d0f9-5cea-4210-aea1-0747966d964d" />

   <img width="1920" height="856" alt="Screenshot 2026-08-24 144234" src="https://github.com/user-attachments/assets/eee11628-e851-445e-ba85-c72404323fd8" />


## 🚀 How to Run

1. Open the notebook in Google Colab
2. Run `!pip install yfinance` to install the required library
3. Run all cells from top to bottom (Runtime > Run all)

## 📅 Project Timeline

Built over 7 days as a structured learning project — from data collection to final analysis and documentation.
