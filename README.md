# Analysis-of-Major-U.S.-Oil-and-Gas-Stock-Prices

Objective: Analyze data from a .csv file that contains information of eight major U.S. oil and gas stocks by creating dataframes, histograms, and gathering statistical information. 

GOAL: The goal of this project is to analyze the stock market prices of major oil and gas stocks over time by utilizing pandas, numpy, and plotly to more easily visualize and gain insights from the data. What I am hoping to achieve from doing this is to create a dataframe from the information contained within a .csv file so that data can easily be seen and interpreted in Jupyter notebook. Also, it is my goal to gather statistical insights from the data and to create histograms that clearly visualize the data. Lastly, I would like to create a function that when a stock symbol is entered as an input the output will display the stock price information for that specific symbol. 

The first step of this project is to utilize a .csv file containing the information of eight major oil and gas stocks over a period of roughly twenty-two (2000-2022) years and to use the data contained in this file in Jupyter Notebook. The information contained within the file consists of the date, symbol, open price, high price, low price, close price, volume, and the type of currency (USD).

Using pandas, a data frame will be created to neatly display the information contained within the .csv along with an index clearly labeling what the information within the rows and columns represents.

By using the information within the created dataframe the quantiles, interquartile range, mean, median, mode, standard deviation, maximum value, and minimum value will be found for the rows: Open, High, Low, Close, and Volume.

An ipywidget will be used so that histograms that were created from the data will be visible in Jupyter notebook and by utilizing plotly histograms will be created to better visualize the data. Separate histograms will be formed for the “Open”, “High”, “Low”, “Close”, and “Volume”. Lastly, a function will be created that can display the data for any specified stock symbol contained within the .csv data.
