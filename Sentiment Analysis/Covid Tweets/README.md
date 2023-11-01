# COVID-19 Sentiment Analysis

## Project Overview

This project focuses on performing sentiment analysis on a dataset of tweets related to the COVID-19 pandemic. The goal is to analyze the sentiment expressed in the tweets and visualize the trends in sentiment over time.

## Data

The data has been sourced from GitHub user **gabrielpreda**'s publicly available dataset on COVID-19 tweets. The dataset includes the following attributes:

- **user_name**: The username of the Twitter account that posted the tweet.

- **user_location**: The location mentioned in the Twitter user's profile.

- **user_description**: A brief description or bio provided by the Twitter user on their profile.

- **user_created**: The date when the Twitter user's account was created.

- **user_followers**: The number of followers the Twitter user has.

- **user_friends**: The number of other Twitter users the account is following.

- **user_favourites**: The number of tweets or posts that the user has marked as favorites.

- **user_verified**: A binary indicator (TRUE or FALSE) that shows whether the Twitter user's account is verified (TRUE for verified, FALSE for not verified).

- **date**: The date and time when the tweet was posted.

- **text**: The content of the tweet, which may include text, links, mentions, and hashtags.

- **hashtags**: Any hashtags included in the tweet, typically preceded by the '#' symbol.

- **source**: The application or platform from which the tweet was posted, indicating the source of the tweet.

- **is_retweet**: A binary indicator (TRUE or FALSE) that shows whether the tweet is a retweet (TRUE for retweet, FALSE for an original tweet).

The dataset consists of 13 attributes and includes over 179,000 tweets related to the COVID-19 pandemic.

## Libraries and Tools Used

The following Python libraries and tools were used in this project:

- `pandas` and `numpy` for data manipulation.
- `matplotlib` and `seaborn` for data visualization.
- `nltk` for natural language processing and sentiment analysis.
- `wordcloud` for creating word clouds.
- `plotly` for interactive data visualization.

## Project Steps

The project includes the following major steps:

1. Data Import: The dataset was imported using `pandas`, and columns relevant to the analysis were selected.

2. Data Preprocessing:
   - Text Cleaning: Text data in the tweets was cleaned by removing URLs, converting to lowercase, and removing punctuation.
   - Stopword Removal: Common English stopwords and specific COVID-19 related terms were removed from the text.

3. Exploratory Data Analysis:
   - Most Common Words: The most common words in the tweets were visualized using word clouds and bar charts.

4. Sentiment Analysis:
   - Polarity Scores: Sentiment polarity scores were computed for each tweet using the VADER sentiment analysis tool.
   - Labeling: Tweets were labeled as 'positive,' 'negative,' or 'neutral' based on their compound polarity scores.

5. Data Visualization:
   - Sentiment Score Counts: The count of tweets in each sentiment category was visualized.
   - Daily Sentimental Analysis: The trend of sentiments over time was visualized on a daily basis.

## Results

The analysis revealed that most tweets expressed a positive or neutral sentiment throughout the dataset. The sentiment trends over time showed that sentiment movement was consistent, with a short period of increased neutral sentiment.

## Usage

You can use the provided code and analysis as a reference for conducting sentiment analysis on text data. Feel free to modify and extend this project for your specific requirements.

## Acknowledgments

- Dataset Source: [COVID-19 Tweets Dataset](https://raw.githubusercontent.com/gabrielpreda/covid-19-tweets/master/covid19_tweets.csv)

## License

This project is open-source and available under the [MIT License](LICENSE).
