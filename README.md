# Covid Tweet Cleaning
A Ministry of Planning is trying to understand the sentiments of people about Covid19. To achive this Twitter a social network platform is used to obtain the data in form of tweets. Tweets are consist of useful information but as well unnecessary data which can cause poor sentiment prediction.
Regular expressions can be used here to perform text search and text replace operations.

# Your Task
Your program will take the path to a ``Tweets_Datset.xlsx`` file and analyze the file for the following operations:

- Remove a words followed by '@'
- Replace '#Covid19' with covid
- Remove words followed by '#'
- Remove 'URL'
- Remove numbers
- Remove '( ' and ')'

Generate a CSV file and store the process results.

# Starter Code
The starter code in ``covid_tweets.py`` has an empty implemetation for ``preprocess_tweets.py``

# Expected Results
 
 Users           | Tweets   
 
 Time4fisticuffs | Trump never once claimed covid was a hoax. We all claim that this effort 
 
 hr bartender    | How covid Will Change Work in General (and recruiting, specifically) 

# Testing
Create a tweet which consists of set of characters we have removed and pass ot to the ``preprocess_tweets.py`` to check the results.
