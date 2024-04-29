# Cryptocurrency Data Retrieval with Python: Automating API Requests

## Introduction
This script retrieves cryptocurrency data from the CoinMarketCap API, automating the process of making API requests, fetching the latest cryptocurrency listings, and storing the data in a structured format. It also includes data transformation, descriptive statistics, market analysis, supply analysis, and visualization.

## Requirements
- Python 3.x
- requests
- pandas
- ipywidgets
- bokeh

## Installation
To install the required dependencies, use the following command:
```bash
pip install requests pandas ipywidgets bokeh


## Usage
Replace 'X-CMC_PRO_API_KEY': 'YOUR_API_KEY' with your CoinMarketCap API key.
Run the script.
View the generated CSV file for cryptocurrency data and explore the analysis.
Code Overview
The script utilizes various libraries for data retrieval, transformation, analysis, and visualization, including requests, pandas, ipywidgets, and bokeh.

## Data Retrieval
The script makes API requests to CoinMarketCap API, retrieves the latest cryptocurrency listings, and stores the data in a DataFrame.

## Data Transformation
The retrieved data is normalized, transformed, and stored in a structured format. Additional data normalization and manipulation are performed for analysis purposes.

## Descriptive Statistics and Data Overview
Basic statistics and an overview of the dataset are computed and displayed, including descriptive statistics for numeric columns, the number of cryptocurrencies per platform, and common tags associated with cryptocurrencies.

## Market Analysis
Various analyses are conducted to analyze market trends, volatility, and performance based on different time intervals. Cryptocurrencies with the highest and lowest price changes are identified.

## Supply Analysis
Analysis is conducted to identify discrepancies between total supply and circulating supply, as well as the proportion of cryptocurrencies with infinite supply. Cryptocurrencies with significant supply differences are highlighted.

## Visualization
Interactive visualizations are created to explore cryptocurrency data, including distribution of cryptocurrencies based on platforms and the relationship between platform characteristics and performance. Price vs. volume analysis is also visualized.

## References
CoinMarketCap API Documentation
Requests Library Documentation
Pandas Library Documentation
ipywidgets Documentation
Bokeh Library Documentation
License
This project is licensed under the MIT License - see the LICENSE file for details.
