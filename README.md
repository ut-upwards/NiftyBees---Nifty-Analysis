# NiftyBEES - Nifty Analysis 


## The Problem Statetment
*  NiftyBeeS is the most popular Exchange Traded Fund (ETF) traded on the NSE. 
*  ETFs have recently become very popular. However this was not the case a few years back
*  Even after being popular and NiftyBeeS being the most popular. ETF still have siginificantly lower liquidity than any popular stock
*  This lower liquidity makes it difficult for efficient price discovery.
* Hence the aim of this analysis was to find insights between Nifty and NiftyBeeS

<br>

<!-- ### **Live Project Link** - (http://heroku.com) -->

 **Concept Used** - Data Analysis, Basic knowledge of Financial insturments

 **Libraries** - Pandas, numpy, yfinance, matplotlib

<br>

## Project Screenshot
![Project Screenshot](/img/SS.png)

<br>

## Results from the Analysis
*  The factor multiplier of ETF price VS Nifty price in 2010-2012 used to be over and around 100. This might be because of even lesser liquidity back then.
*  From 2016 onwards there has been a steady decrease in the factor multiplier.
*  The factor multiplier is still on the downward trajectory but for last 2 years 2020-2022 it has shown extreme variations with few points going well past 2 standard deviation
*  The factor multiplier should be well under 90 by the end of following financial year continuing the trend of 2016
*  Any extreme deviation of 2 standard deviation above or below should give us an opportunity to make a high probability profit beacause of the mean reversion nature of the factor
<br>

## Future Improvements
*  Analysing the ETF price with India Vix data, which is also indicative of fear in the market 
*  This will add a different dimension for analysing the ETF pricing

