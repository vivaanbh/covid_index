# covid_index
Analyzing news articles between Feb 2021 to March 2022 to create a COVID Uncertainty Index which provides a proxy for the sentiment during this period.

Contents:

- Data: articles scrapped from the NYT website.
- Vocab: Building a vocabulary of covid related words.
- Text Cleaning: Stemming, Lemantizing, Tokenisation etc using NLTK package.
- Topic Modelling: exhibit key topics of headlines using the Gensim package.
- COVID & Economic Index: first create a vocab of economic uncertainty words, and eventually create the index as a proportion of articles related to covid and economic uncertainty respectively, to the total articles in that day.
- Market Returns: import data on S&P500 to construct daily returns of the market.
- The Links: visualize the links between the two indices and market returns.
- Vader Sentiment Lexicon: create a daily sentiment plot using the COVID uncertainty Index, which has three dimensions - Negative, Neutral, and Positive.
