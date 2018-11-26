## Twitter-Sentiment-and-Bitcoin-Price

An Intra and Inter-day Market Analysis on Twitter Sentiment and the Bitcoin Market

This study will aim to examine the correlation between Twitter sentiment and Bitcoin market fluctuations. Bitcoin is an extremely volatile cryptocurrency. Determining its key drivers will aid in answering many questions of economists and financiers alike. Many academic journals and publications have identified social media sentiment as a key driver in financial markets. The microblog, Twitter is one of many social media platforms available for public use. This paper will specifically be examining Twitter as a key driver. By using primarily Python and Python packages we will be able to clean, analyze and visualize the data.  A sentiment analysis will be applied to the Twitter data to determine positive (bullish) or negative (bearish) sentiment. This analysis will begin with intraday trading, focusing on market fluctuations from hour to hour. Then interday trading, focusing on market fluctuations from day to day. This study will also extend to tweet volume and Bitcoin price. The result of this study revealed that there is no correlation between Twitter sentiment or tweet volume and Bitcoin price at the intra-day level. There was a moderate inverse relationship defined at the inter-day level. There was no correlation defined between tweet volume at the inter-day level. This study also concluded that Twitter data is unreliable to work with.

Dependencies:

- Python version 3.7
- import re
- import pandas as pd 
- import numpy as np 
- import matplotlib.pyplot as plt 
- import seaborn as sns
- import string
- import nltk 
- import warnings 
- import pandas as pd
- from nltk.stem.porter import *
- from textblob import TextBlob, Word, Blobber
- from textblob.classifiers import NaiveBayesClassifier
- from textblob.taggers import NLTKTagger

- User must have a Plot.ly API

Acknowledgements: 
Ideas from https://www.analyticsvidhya.com were used for the tweet cleaning process. 

Twitter data was obtained through: 
George Washington University Libraries. (2016). Social Feed Manager. Zenodo. https://doi.org/10.5281/zenodo.597278

As Twitter Data is private, the data will not be uploaded
