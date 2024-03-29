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

**003: Geotag Stream**
- Experiment with only getting tweets with coordinates
- Filter out retweets
- Runs for two hours, gets tweets with locations in the US.

**004: Pull Tweets V2**
- Processing Pipeline from 002
- Work directly with results from 003: Geotag Stream
- Cleans, stems, lemmatizes, and part-of-speech tags words from Tweet
- Determine Positive and Negative words
- Compute "Positivity Ratio"
- Prepares data for model building

**005: Data Playground**
- Unpickles dataframe for further testing
