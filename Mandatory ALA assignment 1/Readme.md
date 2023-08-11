The code imports three Python libraries: 
    1. numpy for scientific computing, 
    2. pandas for data analysis, and 
    3. matplotlib for data visualization. 

The code reads the Google stock prices csv file as a pandas dataframe, which is a 2D Array. 
The code converts the date column from string to datetime format using pandas. 
The code extracts the closing price column from the dataframe as a numpy array, which is a 1D array of numbers. 
The code defines the window size for the moving average filter as 30. 
A moving average filter is a technique for smoothing noisy data by computing the average of a window of neighboring data points and replacing the current value with the average. 
The code creates a window array of ones with the same length as the window size and divides it by the window size using numpy. 
This creates a normalized window array that sums up to one. 
The code applies the moving average filter using numpy.convolve(), which performs a convolution operation between 2 arrays. 
The code uses the mode argument as “same” to make sure that the output array has the same length as the input array. 
The code generates a figure with a specified size and plots the original and smoothed data using matplotlib.plot(), which creates a line plot of x and y values. 
The code also sets the x-axis label, y-axis label, title, legend, and displays the plot using matplotlib functions.


References
https://stackoverflow.com/questions/20036663/understanding-numpys-convolve

https://stackoverflow.com/questions/30443883/how-to-smoothen-data-in-python

https://swharden.com/blog/2008-11-17-linear-data-smoothing-in-python/

