# WeRateDogs Twitter Data Wrangling & Analysis

Wrangling, analysing and visualising Twitter data from WeRateDogs, using Python

## Summary

WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

In this project, I gathered, assessed and cleaned data on tweets by WeRateDogs from three sources:

* A given csv file containing an archive of tweets to be analyzed.
* A remotely hosted tsv file containing predictions of dog breed pictured per tweet.
* Data on tweet retweets and favorites obtained via Twitter's API.

I then analyzed the data and reported findings.

Wrangling activities for this project were limited to assessing and cleaning eight quality issues and two tidiness issues.

## Package versions

* python 3.8.5
* numpy 1.20.1
* pandas 1.2.4
* matplotlib 3.3.4
* seaborn 0.11.2
* tweepy 3.10.0

## Instructions

1. Save all files in the same folder, and use Jupyter Notebook to open wrangle_act.ipynb.
2. In section *1.3 Retweets and favorites*, enter your Twitter consumer key and consumer secret.

### Obtaining Twitter Consumer API keys, and the Access Token and Access Token Secret

1. First, if you do not already have one, you need to sign up for a Twitter account.
2. Next, to set up a developer account, follow the directions on Twitter’s Developer Portal, in the “How to Apply” section.
3. You will be guided through the steps, and asked to describe in your own words what you are building.
4. Once you submit your application, you should soon receive an email from Twitter letting you know they have approved your new Twitter developer account. Follow the link in the email from Twitter to a page of directions to get started creating your app.
5. If you are asked for an app name, it can be anything appropriate, and if you’re asked for a Website URL, it can be anything in a standard URL format. You can do the same with other requested URLs, or perhaps leave them blank.
6. If you’re asked to explain how your app will be used, you could say something like "I'm creating this for a student Data Wrangling project, where we need to query and analyze Twitter data from WeRateDogs."
7. You should then be given a Success message, and a new developer page displayed to you where you can manage your app.
8. You can then go to the Keys and Tokens tab on this page to find or generate the Consumer API keys, and the Access Token and Access Token Secret that you will need.

## Files

### wrangle_act.ipynb

Contains the step-by-step analysis and discussion as an interactive Jupyter Notebook.

### wrangle_act.html

Static HTML version of the above.

### wrangle_report.pdf

A report on the wrangling activities performed during this project.

### act_report.pdf

A report on the key findings of this project.

### twitter-archive-enhanced.csv

Given csv file, containing partially processed twitter data in need of cleaning.

## Conclusions

See act_report.pdf

## Credits

This project was provided by [Udacity](https://www.udacity.com) as part of their [Data Analyst nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002). Data were provided by [WeRateDogs](https://twitter.com/dog_rates).


