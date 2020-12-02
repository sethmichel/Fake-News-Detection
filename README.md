# Fake-News-Detection

BUILD 2.1 UNDER CONSTRUCTION, BUILD 2.0 FINISHED<br/>

<br/>Build 2.0
<br/>---Uses a pytorch model to decide how likely it is a given article is fake.
<br/>---Pytorch replaces the API only model version 1.0 used
<br/>---Trained model using a the real and fake datasets from the fake news kaggle compition, totaling about 40,000 articles
<br/>---I'm aware of some improvments I can make to the model, but this version 2.0 model tested at an accuracy of 86.1%
<br/>---Links to all data sets used
<br/>[Kaggle data set](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
<br/>[FakeNewsNet](https://github.com/KaiDMML/FakeNewsNet)


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
