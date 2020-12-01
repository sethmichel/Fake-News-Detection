# Fake-News-Detection

BUILD 2.0 UNDER CONSTRUCTION, BUILD 1.0 FINISHED

Build 1.0: 

---Decides how likely a given article is fake or not based on 120 related articles
---Uses Python, Hoaxy API, Adverify API, and Newspaper API

Handles sites that are:

---Political Bias
---Regularly Imprecise
---Pseudo science, Conspiracy
---Factchecking
---Satire

Does this by:

---Downloading the article
---Gets 100 related articles
---Gets 20 of the most recent related articles
---Gives a site credibility rating of the downloaded article and each of the 120 related articles
---Gives scores to each article
---Summarizes all the scores into 5 truth ratings
---Chooses a truth rating based on the summarized scores, site credibility, and the
   downloaded article site credibility.


Build 2.0 plans:

---Already part way done with a pytorch model to merge with my api calculations
---Will be trained on Kaggle fake news contest data sets, among other smaller data sets
---The CSV file uploaded is what I'm using to clean and combine data sets for pytorch
