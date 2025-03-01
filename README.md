# Cryptocurrency Data Retrieval with Python: Automating API Requests

## Introduction
This script retrieves cryptocurrency data from the CoinMarketCap API, automating the process of making API requests, fetching the latest cryptocurrency listings, and storing the data in a structured format. It also includes data transformation, descriptive statistics, market analysis, supply analysis, and visualization.

## Requirements
- Python 3.x
- requests
- pandas
- ipywidgets
- bokeh

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
- [CoinMarketCap API Documentation](https://coinmarketcap.com/api/documentation/v1/#)
- [Requests Library Documentation](https://docs.python-requests.org/en/latest/)
- [Pandas Library Documentation](https://pandas.pydata.org/docs/)
- [ipywidgets Documentation](https://ipywidgets.readthedocs.io/en/latest/)
- [Bokeh Library Documentation](https://docs.bokeh.org/en/latest/index.html)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

