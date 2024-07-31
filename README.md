# Amazon Sales Data Analysis

This project analyzes Amazon sales data to uncover key metrics, trends, and meaningful relationships between various attributes. The analysis includes extracting, transforming, and loading (ETL) the data, followed by comprehensive visualizations and insights.

## Table of Contents
- [Introduction](#introduction)
- [Data Description](#data-description)
- [ETL Process](#etl-process)
- [Key Metrics](#key-metrics)
- [Sales Trend Analysis](#sales-trend-analysis)
- [Relationships Analysis](#relationships-analysis)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Contributing](#contributing)

## Introduction
With the increasing competition in the market, sales management has become critical for businesses to optimize their distribution methods, reduce costs, and increase profits. This project aims to analyze Amazon sales data to gain insights and improve decision-making processes.

## Data Description
The dataset contains the following columns:
- `Region`
- `Country`
- `Item Type`
- `Sales Channel`
- `Order Priority`
- `Order Date`
- `Order ID`
- `Ship Date`
- `Units Sold`
- `Unit Price`
- `Unit Cost`
- `Total Revenue`
- `Total Cost`
- `Total Profit`

## ETL Process
The ETL process involves:
1. **Extracting** the data from a CSV file.
2. **Transforming** the data by converting date columns to datetime format and extracting additional information like month and year.
3. **Loading** the transformed data for analysis.

## Key Metrics
The key metrics calculated in this project include:
- Total Sales
- Total Profit
- Average Unit Price
- Average Unit Cost
- Average Profit Margin

## Sales Trend Analysis
The sales trend analysis includes:
- Month-wise Sales Trend
- Year-wise Sales Trend
- Yearly Month-wise Sales Trend

## Relationships Analysis
The relationships analysis explores:
- Region-wise Sales and Profit
- Country-wise Sales and Profit (Top 10 countries)
- Item Type-wise Sales and Profit
- Sales Channel Performance
- Priority-wise Sales and Profit

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn

## Setup
1. Here is the google colab notebook link: https://colab.research.google.com/drive/1T2Y7lEeiH7TAwjhKcvsW9weeF2Q_bAgr?usp=sharing
2. Download the data and upload it on google colab and explore the notebook.
## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

