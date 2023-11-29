# Final-Project-
Task One 
Import libraries and install Yahoo Finance 
Data had now been download that contains stocks tickers
 Import  yfinance as yf 
Created a start and end date from the data, this limits the timeline of the data 
 Create a ticker symbol for the banks, and use yf to download the data for yahoo 
Created a list titled tickers with the symbol for each Bank
Used concat to combine SBNY and SIVBQ into one dataframe 
Used df_head() to show the first five rows 
Then to plot using despine to plot for SBNY and SIVBQ
Access the stock data of Amazon, Bank of America etc by using yf.download with previous start and end dates 
Created a  list titled ‘tickers
Use set option to create a maximum  of 36 columns 
 Use concat to combine all six datasets and name the columns Bank Ticker and Stock info 
 Use stocks_head to show the first five rows of the stocks dataframe 
 Accessing all the data frames of stock using yf.download 
Checking for the first five rows using head.()
Using the sames steps the banks dataset using yf.download again
Showing the first rows of the data frame
 Setting columns using columns,names 
Find the maximum number of Close Price using max() . For Amazon its 1149.06
Part Two
Find the maximum number of Close Price using max() . For Amazon its 1149.06
Creating an empty dataframe called returns
Showing the first five rows
Using idxmax() and min to find the dates of the best and worst stock days 
Using despine() to graph the Close column for all six graphs
The worst stock drop aligns the Global Financal Crisis of 2008
Amazon stock stood out for with the pairplot because it was the most constant 
Using sns.pairplot(returns)to plot clusters of the entire returns dataframe
Plotting a histogram using Name of Dataframe['Name_Of_Column'].plot(kind='hist')
Part Three
Plot the 30-day moving averages for JPM CHASE and Morgan Stanley stocks for the first 600 days. Use will need to use the individual data frame that you have create for each stock in Part I.
Creating a start and end date for the first 600 days
Downloading JPM Chase and Morgan Stanley stocks using yf.downloads
Creating a list of ticker symbols 
Creating the data frame called stocks_df1
Combining JPM and MS as one dataframe, naming the columns using pd.concat and columns.names
Creating the 30 day average using window to create the integer, rolling  and plot to create the graph 

