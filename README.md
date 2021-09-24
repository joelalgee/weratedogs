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

Store all files in the same folder, and use Jupyter Notebook to open wrangle_act.ipynb

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


