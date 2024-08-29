# CryptoAPI-Scraper

This repository contains a Jupyter Notebook for retrieving and analyzing cryptocurrency data using the CoinMarketCap API. The notebook performs the following tasks:

1. **API Request:** Fetches the latest cryptocurrency data.
2. **Data Processing:** Normalizes and processes the retrieved data.
3. **Visualization:** Creates plots to visualize cryptocurrency trends.

## Prerequisites

To run the notebook, you need to have the following Python packages installed:

- `requests`
- `pandas`
- `matplotlib`
- `seaborn`

You can install these packages using pip:

```bash
pip install requests pandas matplotlib seaborn
```
# API Key

To access the CoinMarketCap API, you need an API key. Replace 'YOUR_API_KEY' in the code with your actual API key.
Usage

Run the Notebook:
        Open the Jupyter Notebook (.ipynb file) in Jupyter Lab or Jupyter Notebook.
        Execute the cells sequentially to fetch data, process it, and generate visualizations.

Data Retrieval:
        The api_runner function is used to fetch the latest cryptocurrency data from the CoinMarketCap API and store it in a DataFrame.
        The DataFrame can be saved to a CSV file if needed.

Data Analysis:
        The notebook includes code to normalize the data and visualize trends over time.
        You can modify the analysis to focus on specific cryptocurrencies or different time periods.

# Code Overview

API Request: api_runner() function makes a GET request to the CoinMarketCap API and handles exceptions.
    Data Processing: Data is normalized and appended to a DataFrame. The DataFrame is optionally saved to a CSV file.
    Visualization:
        Trend Analysis: Plots percentage changes over different time periods for various cryptocurrencies.
        Price Trend: Creates a line plot of Bitcoin prices over time.
The notebook may require adjustments based on your environment and API access.
    If you encounter rate limits or connection issues, consider adjusting the sleep duration or handling exceptions more robustly.

# Notes

Replace placeholders like `'YOUR_API_KEY'`, `[Your Name]`, and `your.email@example.com` with your actual information. Adjust any sections as necessary to better fit your specific project details.

