# Outsmart-the-Market-Makers-with-Python
Mastering ICT's Market Maker Profiles

## Find more content like this at [Commonstock.com](https://share.commonstock.com/share?inviter=prometheus)

This repository contains a Python implementation of a trading strategy inspired by the Inner Circle Trader (ICT) concepts. The strategy focuses on identifying market maker phases using Simple Moving Averages (SMAs) and visualizing them with the help of Seaborn library.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

- `yfinance`: Fetch stock data from Yahoo Finance
- `pandas`: Manipulate and analyze data
- `seaborn`: Data visualization
- `matplotlib`: Plotting library

### Usage

1. Clone this repository to your local machine.
2. Open the Python script in your preferred code editor.
3. Modify the `ticker`, `start`, and `end` variables to fetch data for the desired stock and time range.
4. Run the script to visualize the market maker phases for the selected stock.

## Strategy Overview

The trading strategy uses ICT's approach to identify market maker phases by calculating the 5-day and 20-day SMAs. The script then applies a crossover strategy and visualizes the accumulation and manipulation/distribution phases using Seaborn.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Inner Circle Trader (ICT) for the inspiration and concepts
- Yahoo Finance for providing stock data
