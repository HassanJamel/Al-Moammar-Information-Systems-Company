<p align="center">
  <a href="https://www.kaggle.com/code/hassanjameelahmed/mis-stock-financial-analysis-2019-2026" target="_blank">
    <img src="AlMoammarMIS-Financials.png" alt="Al-Khaleej-Training" alt="AlMoammarMIS" width="500">
  </a>
</p>
<br>

# Al Moammar Information Systems (MIS) Stock Project Documentation

## a. Project Documentation (PRD)
**Project Title:** Al Moammar Information Systems (MIS) Exploratory Data Analysis & Financial Modeling
**Objective:** To conduct an in-depth exploratory data analysis (EDA), statistical evaluation, and predictive modeling on the historical stock data of Al Moammar Information Systems Company. The aim is to build interactive dashboards and uncover actionable financial insights that can guide investment decisions.
**Scope:** 
- Data cleaning, validation, and feature engineering based on daily historic metrics.
- Time-series forecasting and volatility analysis to track market trends.
- Storytelling and narrative construction regarding MIS's performance within the Saudi Tadawul market.

## b. Dataset Columns and Details
The dataset encompasses comprehensive daily trading metrics structured into the following columns:
1. **Date:** The specific calendar date of the trading session (MM/DD/YYYY).
2. **Close:** The final price at which the stock traded during the market hours. This is the baseline for historic valuation.
3. **High:** The absolute highest price the stock reached during the intraday session.
4. **Low:** The absolute lowest price the stock fell to during the intraday session.
5. **Open:** The initial price at which the stock traded upon the market opening.
6. **Volume:** The total mass of shares traded continuously throughout the market session, indicating stock liquidity and investor interest.

## c. Top 5 Tags
1. Finance & Investment
2. Stock Market
3. Saudi Arabia (Tadawul)
4. Time Series Analysis
5. Data Visualization

## d. SEO-Optimized Project Name and Description
**Project Name:** Al Moammar Information Systems (MIS) Historical Stock Data: Time Series & Financial Analysis
**Description:** Dive into the historic daily trading data of Al Moammar Information Systems (MIS). Explore Open, High, Low, Close, and Volume metrics to perform cutting-edge time series analysis, develop predictive algorithms, and uncover actionable investment insights in the thriving Saudi digital and technology market.

## e. Dataset Coverage
This dataset covers the daily trading activity (pricing and volume) of Al Moammar Information Systems Company (MIS) over approximately 7 years. As a major IT entity listed on the Saudi Exchange, the data reflects how the market reacts to the enterprise’s financial announcements, macroeconomic shifts within the Kingdom's Vision 2030 mandates, and broader global tech sector movements.

## f. Temporal and Geospatial Scope
- **Start Date:** 04/24/2019
- **End Date:** 01/29/2026
- **Geospatial Scope:** Riyadh, Saudi Arabia (Saudi Exchange - Tadawul).

## g. Provenance and Transformations
- **Provenance:** The pristine data originates directly from the Saudi Stock Exchange (Tadawul), which is the sole entity authorized to act as a securities exchange in the Kingdom of Saudi Arabia.
- **Transformations:** Trading prints and individual ticks were aggregated into singular daily intervals (OHLCV format). No extreme transformations, lagging, or imputations were applied previously, preserving the stock values as an exact mirror of market activity. 

## h. Dataset Collecting Methodology
The data was collected via a systematic process utilizing secure financial APIs that interface with historic Tadawul records. Algorithms extracted the parameters daily, parsed the tabular structures, verified integrity against external financial endpoints, and finally formatted the data into a serialized and universally accessible CSV setup suitable for data science implementations.

## i. Biggest Problems and Challenges Facing This Project
1. **Market Volatility:** The Saudi IT sector is subject to sudden fluctuations driven by major government infrastructure contracts, causing noisy data spikes that challenge smooth predictive modeling.
2. **Absence of Contextual Features:** This pure quantitative dataset does not feature external qualitative impacts like news sentiment, earnings reports, or dividend distributions.
3. **Data Stationarity Issues:** The dataset highlights extreme multidirectional trending over its life cycle. Complex detrending and diffing operations are required to make it strictly stationary for traditional statistical evaluation (e.g., ARIMA or SARIMA).
4. **Predictive Overfitting:** Using machine learning models, one risks overfitting to severe market anomalies (e.g., the 2020-2022 disruption periods).

## j. Source of this Dataset
- **True Source:** The Saudi Exchange (Tadawul) Database and corresponding financial aggregators.
- **Link to Official Source:** [Saudi Exchange - MIS Profile (Symbol: 7200)](https://www.saudiexchange.sa/wps/portal/tadawul/home/)

## k. Step-by-Step Problem Development
The overarching financial modeling problem developed in clearly defined historical stages:
1. **Initial Listing & Accumulation (2019):** MIS debuted publicly, presenting a novel opportunity to track one of Saudi Arabia's first pure-play IT firms. The challenge here was limited historic depth for effective training models.
2. **Pandemic & Digital Transformation Boom (2020-2021):** The COVID-19 pandemic initially caused market shocks, followed quickly by a heavy surge in global digitalization. The stock experienced explosive growth, forcing valuation models to completely recalibrate their trend thresholds. 
3. **Market Cooling & High Volatility (2022-2023):** As the tech euphoria cooled down and global inflation concerns spiked, MIS’s stock showed massive price oscillations. For data analysts, constructing algorithms that accurately forecasted support and resistance boundaries safely amidst this volatility became incredibly difficult. 
4. **Current Era - Maturation & Vision 2030 (2024-2026):** Aligning its operations with massive government tech adoption under Saudi Vision 2030 (Data centers, AI, Cloud Computing), analysts need precise historical OHLCV data to measure fundamental strategic shifts against stock performance. This necessitated the compilation of a high-integrity, centralized dataset to accurately interpret if massive corporate investments translated transparently into shareholder value.

[app.md](https://github.com/user-attachments/files/28378427/app.md)
