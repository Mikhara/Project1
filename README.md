# Project 1 DREAM TEAM


## Team Members
	> Jay
	> Mikhara
	> David

# Hypothesis
In terms of risk and return, we hypothesize that an Alternative Investment Portfolio (trading cards and bitcoin) provides a higher Sharpe ratio,  over the last five years, than a Traditional Investment Portfolio (ASX200, Property, ASX Bonds).

An additional hypothesis we hold, is that sentiment, conducted via Reddit posts, affects the Alternative Investment Portfolio and Traditional Investment Portfolio differently and is an important consideration in comprising one's personal Portfolio.

# Research Questions
	1. What is the risk/return ratio for an Alternative Investment Portfolio (trading cards and bitcoin) versus a Traditional Investment Portfolio (ASX, Property, ASX Bonds).
	2. For a more holistic analysis, how influential is social sentiment on:
		a) Trading Cards
		b) Bitcoin
		c) ASX200
		d) Property
		e) ASX Bonds
	3. Over the last 5 years, What is the comparable returns on:
		a) Trading Cards
		b) Bitcoin
		c) ASX200
		d) Property
		e) ASX Bonds


# Why we picked these questions
	> Our individual group members invest in a variety of these strategies from trading cards to crypo and property. We were thus motivated to explore our own personal investments when grouped into an Alternative vs what some might consider a more Traditional portfolio.
	> We were also just really interested in the results for future investment purposes #tradingcards

# Data - where and how
		1. Trading cards (high liquidity cards) - https://www.mtggoldfish.com/sets/Unlimited+Edition
	    
	    2. Bitcoin current price - https://api.alternative.me/v2/ticker/Bitcoin/?convert=CAD
	    
	    3. Bitcoin historical data - https://www.google.com/finance/quote/BTC-AUD
	    
	    4. Government bond (baseline) - https://www.google.com/finance/quote/GOVT:ASX?window=5Y
	    
	    5. ASX200 (general stock market) - https://www.google.com/finance/quote/XJO:INDEXASX
	    
	    6. Property - ABS data in 8 capital cities- https://www.abs.gov.au/statistics/economy/price-indexes-and-inflation/residential-property-price-indexes-eight-capital-cities/latest-release

We used a variety of methods to obtain our datasets, such as:
	1. Google Finance
	2. ASX data
	3. Bitcoin API
	4. Scraped data from https://www.mtggoldfish.com/sets/Unlimited+Edition to obtain trading card prices.
	5. Scraped data from https://redditsearch.io/ to obtain post id to iterate comments on the Reddit API over a specified timeframe. We made a function to change datetime into unix timestamp.
	6. Explored what search terms enabled quality data from 

# Data Exploration

# Data Analysis
	> Risk/Return Analysis by way of:
		> Standard Deviation
		> Correlation
		> Sharpe Ratios

	> We employed a varierty of Graphs:
		1. Line plot
		2. Box plots
		3. Bar Graphs

	>Sentiment Analysis by way of:
		>Defined a function to allocate a score to each of the Reddit comments scraped in various relevant sub-reddit groups.
		> We subtracted the negative from the positive score to provide a value of the sentiment.
		> Plot the sentiment value over time for each of the investments in our Portfolio.

# Implications of our Findings & Assumptions


