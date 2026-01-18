Multivariate Analysis of Tunisian Stock Market Trends
Project Overview
This project examines the financial behavior and market dynamics of companies listed on the Tunisian Stock Exchange (BVMT) using multivariate statistical analysis and machine learning techniques. By applying Principal Component Analysis (PCA) and Linear Regression, the study extracts meaningful patterns from historical data to explain stock price fluctuations and identify latent market factors.

Technical Stack

Language: R 


Key Libraries: FactoMineR (PCA), ggplot2 (Visualization), dplyr (Data Manipulation), corrplot, car.


Methodologies: Exploratory Data Analysis (EDA), Dimensionality Reduction (PCA), Predictive Modeling (Linear Regression).

Key Research Objectives

Exploratory Analysis: Describe behavioral patterns and trends in stock prices, trading volumes, and returns.


Dimensionality Reduction: Use PCA to simplify high-dimensional financial data into uncorrelated latent factors.


Predictive Modeling: Evaluate how trading volume and volatility influence stock price movements.


Decision Support: Generate data-driven insights for portfolio diversification and risk analysis in emerging markets.

Methodology & Workflow

Data Preprocessing: Implemented cleaning, Z-score normalization, and monthly aggregation to reduce noise and standardize variables (Closing Price, Volume, Volatility, and Returns).


Multivariate Analysis (PCA): * Identified that the first two principal components explain 57.48% of the total variance.


Dim.1 (Market Activity): Captured liquidity and volatility.


Dim.2 (Performance): Reflected price returns independently from market volume.


Regression Modeling: Developed a linear framework to test the impact of volume and volatility on stock prices.

Principal Findings

Market Structure: Trading volume and volatility are major drivers of market dynamics, while stock returns often operate as an independent dimension.


Volume-Price Link: A positive correlation exists between trading volume and price increases, suggesting price appreciation often aligns with higher market activity.


Independence of Returns: Financial performance (returns) is frequently driven by external factors such as earnings announcements or investor sentiment rather than just price scale
