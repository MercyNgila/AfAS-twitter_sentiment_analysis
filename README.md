# Sentiment Analysis of Tweets  

## Description

Welcome to the project on Natural Language Processing and sentiment analysis of COVID19-related data from Twitter! From the tutorials you will learn the following:

- *Tutorial 1* Collect and Clean Twitter Data
- *Tutorial 2* Perform sentiment analysis using existing toolkits
- *Tutorial 3* Perform sentiment analysis using machine learning


## Data

The dataset consists of ~4000 tweet texts collected from Twitter using the Twitter API. These data were collected in over June-July 2020 and are all related to COVID-19. If you would like to try the generalised version of this project please see the [ twitter_sentiment_analysis
](https://github.com/Hack4Dev/twitter_sentiment_analysis) repository.  

This project makes use of supervised machine learning, therefore the data have all been assigned sentiment labels, i.e. either 0, 1, or 2 corresponding to tweets with either negative, neutral or positive sentiment, respectively. 

In order for you to run the code in Tutorial 1 which allows you to collect tweets, you will need to set up a Twitter developer account and obtain certain API authorisation credentials. This can be done by followin g the instructions set out in the [Twitter API v2 setup.pdf](https://github.com/Hack4Dev/twitter_sentiment_analysis/blob/master/COVID19_Twitter_Project/Twitter%20API%20v2%20setup.pdf) file.

## Hackathon Task

Think of a research question where sentiment analysis can be used to gain insight into a topic of interest!  

For example: What are people's sentiment toward a product, situation, disease or their government in various countries? Think of what insights you would like to obtain around your research question. Be as creative as you'd like!  

You will need to:  

- Collect Twitter data from one or multiple regions in the world, relevant to your research question.  
- Prepare the data (by cleaning and/or pre-processing).  
- Make use of existing sentiment analysis tools or one of the trained machine learning models to predict sentiment of your collected tweets.  
- Draw some conclusions and present your findings.


## Prerequisites

All the libraries/dependencies necessary to run the tutorials are listed in the [requirements.txt](https://github.com/Hack4Dev/twitter_sentiment_analysis/blob/master/requirements.txt) file.


## Installation

All the required libraries can be installed using pip and the [requirements.txt](https://github.com/Hack4Dev/twitter_sentiment_analysis-1/blob/master/requirements.txt) file in the repo:

```bash
> pip install -r requirements.txt
```

### Would you like to clone this repository? Feel free!

```bash
> git clone https://github.com/Hack4Dev/twitter_sentiment_analysis.git
```

Then make sure you have the right Python libraries for the tutorials. 


### New to Github?

The easiest way to get all of the lecture and tutorial material is to clone this repository. To do this you need git installed on your laptop. If you're working on Linux you can install git using apt-get (you might need to use sudo):

```
apt install git
```

You can then clone the repository by typing:

```
git clone https://github.com/Hack4Dev/twitter_sentiment_analysis.git
```

To update your clone if changes are made, use:

```
cd twitter_sentiment_analysis/
git pull
```

-----
