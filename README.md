# Open-Interest-Plots
Based on a specified stock ticker symbol, this code generates plots of all open interest on the options chain on all available expiration dates.

Options data is downloaded with `yfinance` and visualized for open interest of Calls and Puts by strike price and expiration date.

## Installation

Needed Python modules:
pip install yfinance matplotlib pandas

## Usage

The Jupyter Notebook `Open_Interest_per_Expiration.ipynb` contains the complete code. Run it to load the data and create graphs.

## Data source

The option data comes from Yahoo Finance via the `yfinance` library.

## Results

For each expiration date, bar charts are generated showing the open interest for calls and puts per strike.

## License

This project is licensed under the MIT license.
