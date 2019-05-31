_# Predicting BAT prices. 

Creating a price predictor for bat using growth statistics. 

The purpose of this exercise is to predict the price of BAT using growth statistics. 
To attack this problem we will need the following ingredients: 

1. Historical data for bat growth.
2. Corresponding pricing data for the same period as the historical data
3. A simple predictive model that tries to predict the price of bat given historical data

Let’s dig in:
 Let's start by scraping historical data for growth. These, including historical data for youtube, website and twitch publishers, as well as the number of BAT holders can be found at https://batgrowth.com/ Can you write a scraping script or otherwise scrape these numbers from batgrowth.com ?
The next step is to obtain some pricing data. For this we will use coinmarketcap.com Can you write another script or otherwise scrape historical pricing data for bat from https://www.coinmarketcap.com ?
We now need to put together the growth and pricing data. You need to match growth data to pricing data for each day in the downloaded history. This will comprise dataset for your next step. 
Having assembled our dataset we are now able to try and make price predictions for BAT using the growth numbers. We can do that with a simple model like a linear regression or a random forest from sklearn (https://scikit-learn.org/), or whatever other machine learning package you may be familiar with. What's the initial prediction loss for this model. 
Are there any particularly strong pricing indicators on the historical dataset? How would you go about improving your model? Is it possible to make better predictions by transforming your historical data somehow?
Are there any particularly predictable or unpredictable time periods in your historical model? 

Please use any tools/libraries you find necessary for achieving the individual steps of the assignment, as well as any additional data sources you feel may improve the price of prediction. If there is an off-the-shelf solution for any of the steps that would make you proceed faster feel free to use it. 

It’s recommended to create a gist of the data and code you used in your solution as well as a short writeup of the steps you took to arrive there (2 or 3 paragraphs for the entirety of the process should be enough). 
Good luck! 

