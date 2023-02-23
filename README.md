# Prediction-of-Cryptocurrency-Trends
Problem Statement:
Bitcoin and Ethereum are two of the largest
cryptocurrencies. These are digital money 
that runs independently of any central 
authority or government monitoring. Peer-to-peer software and cryptography are used 
instead. These were founded with the 
intention of allowing people to send money 
over the internet. 

In this project, we're attempting to 
determine whether global news i.e., tweets
concerning Cryptocurrency-related issues 
has an impact on the price of a Bitcoin and 
Ethereum. Our project aims to forecast the 
change in the dollar value, i.e., whether the 
price will rise or decline in response to the
world news.

Implementation:

Data Extraction: We have imported the 
Bitcoin and Ethereum data from 
OpenBlender into Panda Data frames.

Exploratory Data Analysis: Post extraction 
we have calculated several insights out of 
the original datasets using basic logarithmic 
and plotting functions and computed a target 
variable.

Data Blending: Further we have blended 
our cleaned data with the dynamic
cryptocurrency data available on 
OpenBlender using the time stamps and the
tweets that were made in the news about the 
cryptocurrencies on that particular day.

Polarity Evaluation: We used this 
blended data to calculate a polarity score of 
a tweet for a particular timestamp, categorized 
it as positive negative or neutral and 
established a relationship between the variation 
of price and the polarity score on that date
and analyzed those visualizations.

LSTM Model Building: Next, we established an LSTM model for each 
cryptocurrency that is Bitcoin and Ethereum. 
Splitted the data into training and testing. Fitted the 
model and calculated the performance
measures.

Cryptocurrency Prediction: Lastly, we 
used the established model to predict 
the changing rates of Bitcoin and Ethereum 
cryptocurrencies over the next 60 days or for 
any time frame as per our desire.
