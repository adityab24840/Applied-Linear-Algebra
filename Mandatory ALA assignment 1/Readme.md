# Stock Price Smoothing using Moving Average Filter

This repository contains a Python script that demonstrates how to use a moving average filter to smooth noisy stock price data. It utilizes popular libraries like NumPy, pandas, and Matplotlib for data manipulation, analysis, and visualization.

## Description

The provided Python script performs the following steps:

1. Imports the necessary Python libraries:
   - `numpy` for scientific computing
   - `pandas` for data analysis
   - `matplotlib` for data visualization

2. Reads a CSV file containing Google stock prices into a pandas DataFrame.
3. Converts the date column from string to datetime format using pandas.
4. Extracts the closing price column from the DataFrame as a NumPy array.
5. Defines a window size of 30 for the moving average filter.
6. Creates a normalized window array with ones divided by the window size using NumPy.
7. Applies the moving average filter using `numpy.convolve()`, using the mode argument "same" to maintain output length.
8. Generates a line plot with Matplotlib to visualize both the original and smoothed data.
9. Sets labels, title, and legend for the plot.

For more details on the moving average filter and its implementation, refer to the provided references.

## Usage

To run the script and see the stock price smoothing in action:

1. Clone this repository to your local machine.
2. Make sure you have the required libraries (`numpy`, `pandas`, and `matplotlib`) installed. You can install them using `pip`:
3. Load `GOOG.csv`  CSV file that containing stock price data.
4. Run the script using a Python interpreter:


## References

1. [Understanding NumPy's Convolve](https://stackoverflow.com/questions/20036663/understanding-numpys-convolve)
2. [How to Smoothen Data in Python](https://stackoverflow.com/questions/30443883/how-to-smoothen-data-in-python)
3. [Linear Data Smoothing in Python](https://swharden.com/blog/2008-11-17-linear-data-smoothing-in-python/)
