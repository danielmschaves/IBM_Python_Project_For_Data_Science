# IBM Python Project For Data Science

## Repository Overview
This repository contains a Python project that extracts and visualizes stock and revenue data for Tesla (TSLA) and GameStop (GME). The objective of this project is to enable users to understand the historical trends in share prices and revenues for these two companies. The repository includes the main Python script or Jupyter Notebook, along with the necessary dependencies.

## Phases:
- Data Extraction
In this phase, we will extract stock and revenue data for Tesla and GameStop. We will use the yfinance library to obtain stock data, and web scraping techniques (using the requests and BeautifulSoup libraries) to extract revenue data from relevant websites.

- Data Processing
After extracting the data, we will process and clean it to ensure that it is suitable for visualization. This includes removing unwanted characters (e.g., commas and dollar signs) and handling missing or empty values in the data.

- Graphing Function
In this phase, we will define a graphing function (make_graph) that accepts stock data, revenue data, and the stock name as inputs, and generates interactive visualizations using the Plotly library. This function will be used to visualize the data for both Tesla and GameStop.

- Data Visualization
Finally, we will use the make_graph function to create visualizations for the extracted data. The visualizations will display historical share prices and revenue data for Tesla and GameStop, up to June 2021.

## Conclusion
This project demonstrates an efficient approach to extract, process, and visualize stock and revenue data for Tesla and GameStop. The visualizations generated will help users better understand the historical trends in share prices and revenues for these companies, which can assist in making informed decisions related to stock market investments.
