
# Download and Process Trading Data from Binance

## Information about scripts:

* The `download_binance_data.py` script is a working version that allows to download the trading data (OHLC, Volume, Trades, etc.) from `Binance` via `Binance API`.
The script downloads the data per a symbol and stores it within a directory as a .csv file.

* The `process_binance_data.py` script is created to generate OHLC, Volume tables separately for a number of symbols within one table. This format is handy while designing trading strategies. It is assumed that the input data for this script is downloaded from `Binance` via `Binance API` using `download_binance_data.py`. <br> The script was created to efficiently utilize `NumPy`. The tool is useful to process massive dataframes with time-series of frequent data (seconds, minutes, etc.).


