# Fake-News-Detection

BUILD 2.0 UNDER CONSTRUCTION, BUILD 1.0 FINISHED<br/>

<br/>Build 1.0:
<br/>---Decides how likely a given article is fake or not based on 120 related articles
<br/>---Uses Python, Hoaxy API, Adverify API, and Newspaper API

<br/>Handles sites that are:
<br/>---Political Bias
<br/>---Regularly Imprecise
<br/>---Pseudo science, Conspiracy
<br/>---Factchecking
<br/>---Satire

<br/>Does this by:
<br/>---Downloading the article
<br/>---Gets 100 related articles
<br/>---Gets 20 of the most recent related articles
<br/>---Gives a site credibility rating of the downloaded article and each of the 120 related articles
<br/>---Gives scores to each article
<br/>---Summarizes all the scores into 5 truth ratings
<br/>---Chooses a truth rating based on the summarized scores, site credibility, and the
<br/>   downloaded article site credibility.

<br/>Build 2.0 plans:
<br/>---Already part way done with a pytorch model to merge with my api calculations
<br/>---Will be trained on Kaggle fake news contest data sets, among other smaller data sets
<br/>---The CSV file uploaded is what I'm using to clean and combine data sets for pytorch
