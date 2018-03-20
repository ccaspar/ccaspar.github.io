---
layout: default
modal-id: 3
date: 2018-02-20
img: reddit.png
alt: image-alt
project-date: February 2018
category: Data Science
description: <b>Overview</b><br>This project was an exercise in webscraping and natural language processing and well as comparing random forests with other classifiers. The goal was to use data scraped from reddit to analyze drivers of user enagement, measured by number of comments. For this study, I classified the target into a binary variable &#8212 above or below median number of comments, with accuracy as the scoring metric.<br><br><b>Data</b><br>HTML data was scraped from reddit (http://www.reddit.com). The web scraper retrieved data from the 'front page' of reddit and all following pages (there are 20 following pages). HTML data was then processed into key variables through feature selection and put into a pandas dataframe. Lastly, feature engineering was performed on the titles of the posts.<br><br> <b>Key Insights</b> <br>Both the random forest and the logistic regression achieved accuracy scores in the low 70s, a certain improvement over the baseline of 50%. Part of the model tuning was the decision to include a countvectorizer. In this case, I do not believe the dataset has enough word data for the countvectorizer to be effective. For effective use of the countvectorizer, more data should be gathered, or the analysis should be performed on posts within a single subreddit (topic) where certain buzzwords and trends are more likely to exist.<br><br><b>Skills and Concepts Used</b><br>Pandas<br>SKLearn<br>BeautifulSoup<br>Regex<br>CountVectorizer<br>Feature Engineering<br>Random Forest<br>Logistic Regression<br><br> <a href="https://github.com/ccaspar/reddit_data"> Link to project on github </a>


---
