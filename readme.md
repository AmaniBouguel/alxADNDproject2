# ALX Data Analysis Project2 Readme

## Introduction
This project was developed as a part of ALX Africa-Udacity Data Analysis NanoDegree. It aims to make into practice acquired knowledge about data wrangling. </br>
The main task in the project was gathering data, assessing it then cleaning it. Data is composed from different dataset of different sources. It is not clean at all. Hence, it was asked to find only 8 quality issues and 2 order issues. </br>
After cleaning Data, we need to store it and to draw some visualization to explore data

## Dataset to be analyzed
The data to be analyzed in this project are users tweets in Twitter @dog_rates known as ["WeRateDogs"](https://en.wikipedia.org/wiki/WeRateDogs). This data is special as the rating is higher than the denominator.</b>
The datasets are retrieved from several sources:
1. CSV file to be read using Pandas and stored in a dataframe
2. TSV file to be retrieved using Requests API then stored in a dataframe
3. Twitter using tweepy API, stored later in a json file to be read by Pandas and saved in a dataframe

## Project content
1. wrangle_act.ipynb: It is the jupyter notebook used to develop Python code
2. wrangle_act.html: it is the HTML version of wrangle_act.ipynb
3. twitter_archive_enhanced.csv: it the WeRateDogs Twitter archive data
4. image_predictions.tsv: it is the tweet image prediction downloaded using Requests library
5. tweet_json.txt retrieved using tweepy API
6. twitter_archive_master.csv: It is the stored data after wrangling phase
7. wrangle_report.pdf: it is can be used as an internal documentation. It describes data gathering, assessing and cleaning steps.
8. act_report.pdf: This document contains some visualization used to explore data. It can be used as a source documentation for a magazine article
