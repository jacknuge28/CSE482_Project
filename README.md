## CSE 482 Project Notebooks
### Jack Nugent
Sentiment Analysis on Tweets Mentioning Elon Musk

**001: Project Exploration**
- EDA of Tweepy and NLTK structures.
- Plays with Client and StreamingClient objects
- API `search_tweets()`
- Explore fields of Tweet objects from Tweepy
- Basic NLTK Exploration
- Thoughts for future project steps

**002: Pull Tweets**
- Paginator to pull large amounts of Tweets matching a query
- Filters retweets, some slip through?
- Tracks Geolocation, not many hits
- Saves data as JSON, loads from JSON into Pandas DF
- Preprocessing of text field
- NLTK processing of text field
- Has Stemming, Lemmatizing, POS Tagging
