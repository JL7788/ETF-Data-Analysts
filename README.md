# ETF-Data-Analysts

This is a python program that will allow users to analyze the performance of an asset from the etf database that was provided. SQL queries were used to get the data and statistics like daily returns, closing prices, volume, and much more.
<br />
## Technologies

This project uses python 3 with jupyter notebook
<br />

## Installation Guide

Before running the application first import:<br />

-numpy<br />
-pandas<br />
-hvplot<br />
-sqlalchemy<br />



## Findings/Analysis 
I started by making the connection to the database and creating the engine. Once this was completed. I queried all of the columns from paypal and created an interactive plot with the daily returns column. This was repeated for the cumulative returns as well. <br />

This process was repeated for specific columns as well. Limit was also used to give the top 10 daily returns for better analyzation.<br />

Next I joined multiple columns together and averaged all the daily returns into one dataframe in order to calculate daily returns, cumulative returns, and graph the results. 

<br />


## Contributors

Jeffrey Liu : Dev
UCB Fintech - Provided initial resources


## License
Trilogy Technology 
UCB Fintech Extension Program



