# Sentiment Analysis

# Introduction
In this project, I explore English language tweets containing Putin, Lukashenka, Russia, Zelensky, Ukraine, Kyiv, Kharkiv, Chernihiv, Mykolaiv, or Mariupol.The tweet data is retrieved using the Twitter Developer Platform and spaCy models are used for natural language processesing. <br>

Use this worksheet to update the query and conduct your own research!

# Setup
1. Get your own token to the Twitter API at: 
https://developer.twitter.com/en/portal/petition/essential/basic-info

2. Once created, save your bearer token to a plain text file, with a .yaml extension:
BEARER_TOKEN: "replace text with your token here"

3. Decide the topics that you'd like to include. Refer to this page for filtered stream syntax: 
https://developer.twitter.com/en/docs/twitter-api/tweets/filtered-stream/integrate/build-a-rule

4. Update and run the notebook:
https://github.com/tdubon/SentimentAnalysis/blob/main/Twitter_SentimentAnalysis_Final.ipynb


# Saving custom model
If you intend to monitor the topic or train a model over additional examples in the future, you can save and load the same model, that is expected to improve its predictive performance. The code is included and you can read more about it:
https://spacy.io/usage/saving-loading#models
