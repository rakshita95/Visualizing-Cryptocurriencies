# Analyzing the cryptocurrency market

We analyze historical cryptocurrency data to better understand the cryptocurrency investment. We also look for possible existing relations between the cryptocurrency market and the stock market. 

This analysis was part of the final project for Exploratory Data Analysis and Visualization course in Spring 2018.

## Interctive visualizations

Using D3, we made a playable movie that displays the change of correlation over time, with the period in time in reference to a static display of the price level of each market. The movie can be played to show the change of correlation over time. We also include a slider bar that can be dragged to change the period in time. The dynamic changes in correlation are visualized with an attractive animation.

Link: https://bl.ocks.org/rakshita95/raw/49bd209bc85d095e6b16b5449ae2914e/f3751247214bd1611a8ecc09d5c6fec15a6d3f17/

Using the Shiny app, we reproduced several of our graphs in our report but we allow the user to select the interval of time over which the price data is analyzed. Thus the user selects the start date and end date for the data to be analysed according to the user’s interest. He or she can also leave the default values to 2013 or 2018, or change it using the controls on the slider.

We essentially show the trends in the data for Bitcoin and S&P 500 by visualizing their graphs for Seasonality in weekly price change patterns for the date ranges chosen by the user. This is one of the options to check compare the two assets.

The second option is to check the monthly price change patterns for the two assets.

We also visualize an investment strategy of how the returns produced with a 30-day buy-sell investment strategy under any interval of time chosen by the user for Bitcoin and S&P 500.

We expect this to be a fascinating tool to use for the user. Our primary intention behind the tool is to make the user aware of the trends in the two assets based on historical data and gain insights for making a decision to invest in either.

Link: https://ijupudy.shinyapps.io/crypto2/

## Other contents
analysis.pdf documents the approaches taken, static visualizations, and our observations.   
analysis.Rmd contains the relevant R code 
