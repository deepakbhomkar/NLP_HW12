# NLP_HW12
NLP homework 12

# Crypto Sentiment

In this exercise we have applied natural language processing (NLP) to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum.
Additionaly we have applied fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

## Sentiment Analysis

Using the sentiment analyzer, it as found that Ethereum had highest mean positive score compared to Bitcoin. The news was more focused on Etehreum when compared to Bitcoin for this set of data as seen in the screen shot below

### Bitcoin Sentiment

![Bitcoin Sentiment](Instructions/Images/Bitcoin_Sentiment.png)

### Ethereum Sentiment

![Ethereum Sentiment](Instructions/Images/Ethereum_Sentiment.png)

## Natural Language Processing

In this activity the text for each coin was cleaned and stored as tokens. The following activities were perfoemd to clean the text and tokenize it:

1.  Create a list of the words
2.  Convert the words to lowercase
3.  Remove the punctuation
4.  Remove the stop words    
5.  Lemmatize Words into root words

The Bigrams were determined for both the coin sentiments and the top 10 words were as below for each of the coins:

### Bitcoin Top 10 words

![Bitcoin Top 10 Words](Instructions/Images/Bitcoin_top10words.png)

### Ethereum Top 10 words

![Ethereum Top 10 Words](Instructions/Images/Ethereum_top10words.png)


### Bitcoin Word Cloud

![Bitcoin Word Cloud](Instructions/Images/Bitcoin_wordcloud.png)

### Ethereum Word Cloud

![Ethereum Word Cloud](Instructions/Images/Ethereum_wordcloud.png)

## Named Entity Relationship NER 

The named entity relationships for both the coins were carried out using Spacy and entities showed up as person, org, product, ordinal, date , GPE or money.