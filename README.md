1.) Goals of this project:

-Practise data extraction from Twitter

-Generate online identity of a Twitter User

2.) Features implemented:

-Twitter data extraction.

-Sentiment Analysis of the tweets posted and liked by a user.

-Extraction of Named Entities from the tweets posted and liked by a user using Named Entity Recognition

-Identifying the top 15 accounts the user interacts with

3.) Tech Stack of this Project:

-Language: Python3

-Dependencies: Stanford NER Tagger

-Libraries: Available in requirements.txt.

4.) To run this Project:
Clone this repo and pip install the requirements
git clone https://github.com/VirtualGoat/Twitter-Profile-Analyzer.git
cd Twitter-Profile-Analyzer
pip install -r requirements.txt
python main.ipynb

Flow of project:
User specifies the username that is to be analyzed

The name of the specified user and their location(if mentioned on Twiiter) is displayed.

A graph displaying the sentiments of tweets posted by the user in the specified time. Which include:

Polarity 0 = Neutral Sentiment

Polarity 1 = Positive Sentiment

Polarity -1 = Negative Sentiment

Detection of nouns mentioned in the tweets posted by the user in the specified time.

Detection of named entities which consist of Organization, Person and Location mentioned in the tweets posted by the user.

A graph displaying the sentiments of tweets liked by the user. Which include:

Polarity 0 = Neutral Sentiment

Polarity 1 = Positive Sentiment

Polarity -1 = Negative Sentiment.

Detection of nouns mentioned in the tweets liked by the user since the user created their account.

Detection of named entities which consist of Organization, Person and Location mentioned in the tweets liked by the user since the user created their account.

Printing top 15 usernames and locations of the users whose tweets were liked most frequently.
