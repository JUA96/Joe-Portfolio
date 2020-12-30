# Joseph Arber 

## Welcome 👋
Hi, I am Joe and welcome to my GitHub Portfolio! The purpose of this portfolio is to showcase the range of different data driven projects and analyses I have undertaken over the past few years. 

## Background 🙋🏽‍♂️
I currently work as a Data Analyst for a DTC e-commerce startup. I come from a political science background having completed my Bachelors at [SOAS, University of London](https://www.soas.ac.uk/about/) in Politics & Economics. Following this i took an Master of Science degree at [UCL](https://www.ucl.ac.uk/public-policy/), majoring in public policy analysis. On this gradute course there was a strong empahsis on using computational methods to extract insights and generate conclusions from large public datasets. In conducting this analysis I was introduced to R progamming and have been hooked ever since. Building on my training in computational social sciences I decided to move into the field of data science.  

## Interests 🔭 
I am interested in innovative developments at the intersection of Data Science and Public Policy making. In particular, I am fascinated by the positive impact that open source colloboration and new technologies can have on our governance and policymaking processes. I truly believe that there is massive room for innovation in how our institutions function and make decisions.

My other interests are lie somewhere in between geopolitics and political trends across emerging economies. For example my masters dissertation focussed on the relationship between Chinese finance and state-level governance across Africa. Specfically, I wanted to measure the impact of Chinese lending on corruption levels and regulatory quality at both the state and firm level over a 10-year period. Although I deployed several statistical techniques to produce this report I was also able to draw on my qualitative skills to contextualise the quantitative findings. I enjoyed this part the most! The paper is [here:](https://www.researchgate.net/publication/338580894_A_Multi-Method_Analysis_of_the_impact_of_Chinese_non-concessional_finance_on_state-level_governance_in_Africa) 

I often try to bring my thoughts and ideas about the world together, you can find this in my blog! Alongside this blog, I also contribute to a daily newsletter run by some politically engaged friends over at Polis Analysis. That can be found [here.](https://www.polisanalysis.com/blog/polis-snapshots-what-is-polis-analysis-doing-to-address-the-problem-of-fake-news)

## Skills 👨🏽‍💻
Alongside my political science training I have also gained experience in the data science. I am a big fan of statistical modelling in R, but I also have produced machine learning models with Python. Over the next few months, maybe years... I would like to build a substantial portfolio of R and Python projects, leveraging the various advantages of each language to build interesting and useful models, tools and apps.


One of the areas I would like to focus on is using Natural Language Processing methods to extract insights from Social Media (Twitter, Facebook etc...) With the amount of data produced on social media there is an enormous need to analyse and establish trends/patterns in the mined datasets. The use cases could be in fields of counter extremism, combatting fake news, political and business strategy and generally being useful in helping to better understand public opinion across the digital world!

If you would like to colloborate or share ideas with me please do get in touch at:

- `Email`: joseph.arber1@gmail.com
- `Linkedin`: https://www.linkedin.com/in/josepharber/


### Domain Knowledge:

- Political Science and Economics 
- Econometrics and Statistics
- Behavioural Science
- Public Policy Evaluation
- Business Strategy

### Data Science AOI:

- Sentiment Analysis
- NLP
- Geospatial 
- API/Json 
- Social Media Network Analysis

### Statistical/Econometrics Expertise:

- Time-series
- Panel Data 
- Bayesian Modelling
- Multilevel Regression Modelling
- Logistic Regression
- Generalized Additive Models (Smoothing Functions)
- Synthetic Control

### Technical Skills:

- Data Analysis, EDA & Hypthesis Building
- Predictive Analytics, Inferential Modelling
- Machine Learning (Classification, Regression, Clustering)
- Data Mining, Web Scraping

### Language Expertise:

- Python
- R
- SQL 

### IDEs:

- RStudio
- Jupyter Notebooks
- VS Code
- Atom


## 🛠 My GitHub Portfolio:

**My GitHub page showcases a number of data science projects I have worked on. I regularly add to this portfolio with new programming projects that are of interest to me.**

Here are a couple of examples of some of the **data science projects** i have worked on:

### 1. Fake News Classifier 

**Project Overview:**

The project sought to succesfully predict whether an unseen news article was 'fake or real. This entailed using several machine learning algorithms that could effectively classify 100,000 articles. 

- Using Natural Language Processing techniques I classified 150,000 news articles. The algorithms used were Support-Vector Machine (SVM), Multinomial Naive-Bayes (MNB), and XGBoost (XGB), of which SVM was the most successful with a **97%** accuracy.

![](/Screenshot%202020-12-29%20at%2017.45.00.png)

The project is here: [Fake News Classifier](https://github.com/JUA96/fake-news-classifier)

Software used: 

- Python
- Jupyter Notebooks

Key Package Dependencies:

- Tweepy
- NLTK
- Spacy
- Sklearn

### 2. Geospatial Analysis of London Borough's

**Project Overview:**

The project set out to see if we could predict London's house prices by the amount of well rated locations and venues in each borough. 

- Using the Four Square API to mine location data, I segmented venues and locations based on the London borough they reside in. I then used these segments to cluster the data based on the average value of a property for each borough. I subsequently mapped this data to geographically explore the variation in house prices in respect to venue density.

- Deploying K-Means clustering techniques I succesfully predicted which **price segment** a borough would fit into based on the type of venues that were in it.

Significant predictors of house price variation across boroughs were **proximity to 5-star restaurants, museums and other well rated venues.**

Data Acquisition: 
- Four Square API venue data. Loaded data in JSON format then converted it to a pandas df.

1. London's property prices data from the london data store: https://data.london.gov.uk/dataset/average-house-prices The dataset contained the 'year', 'average value', 'borough', 'measure', we also added the latitude and longitude values for each borough in order to carry out the analyses.

2. Geospatial data from http://martinjc.github.io/UK-GeoJSON/json/eng/topo_eer.json in JSON format allowed us to conduct the geospatial analyses, specifically mapping the property prices to the clustered location data.


The project is here: [London Geospatial](https://github.com/JUA96/Capstone-Project-Geospatial-Analysis)

Software used: 

- Python, IBM Watson Cloud

Key Package Dependencies:

- Sklearn
- Geopandas
- bs4
- json requests
- folium
- geopandas
- geopy

### 3. Predicting US Border Crossings 

**Project Overview:**

The project goal was to see if it was possible to forecast US Border Crossings volumes. Specifically, I wanted to predict which states and ports, entrants would arrive through, as well as establish how likley it was the entrants would arrive on foot or by car. 

- Deploying various time-series forecasting models ARIMA and Random Walk, I succefully predicted the volume of entrants over the next 5 years. 

The project is here: [US Border Crossing Predictions](https://github.com/JUA96/VScode-ML-projects-python/blob/master/US-Border-Data.ipynb)

Software used: 

- Python, VS Code IDE

Key Package Dependencies:

- Sklearn
- geopandas
- scipy
- plotly
- calendar
- statsmodels
- json

### 4. What influences European Voter Preferences?

**Project Overview:**

This project was completed as a requirement for a quantitative methods module at graduate school. Using the European-Social Survey dataset I wanted to explore which factors determined how a respondent was likley to vote in respect to levels of EU integration. This was a fairly straightforward Logistic Regression problem, but I did arrive at some predicted probabilities for how likley a respondent would vote leave based on their age, sex, employment and trade union status. 

The project is here:[EU Voting Preferences](https://github.com/JUA96/logistic-regression-in-R/blob/master/EU-voting-preferences.Rmd)

Software used:

- R studio, R Markdown

Key Package Dependencies:

- tidyverse
- dplyr
- foreign
- ggplot2
- caret 
- aod 

### 5. Understanding the British Welfare State System: "What causes welfare recipients to fall into arrears?" 

**Project Overview:**

A descriptive and statistical data analysis of the UK welfare state system.

The aim of this analysis was to explore the main themes and trends behind the welfare payments system in the UK. However, given the size of the dataset, this specific projects timeframe and intended audience, the scope of the analysis was narrowed down to focus on a few key questions. Notably, the analysis carried out tried to gain a better understanding through two dimensions:

1. Qualitative Understanding: What are the main drivers of welfare claims, and what are the key reasons for failure to meet debt repayments?

2. Quantitative Understanding: Is housing benefit enough to sustain rent? Does universal credit cover monthly costs?

Specifically, this analysis wanted to invesigate what welfare and benefit features included in the dataset are most correlated with a users inability to manage debt repayments. Alongside this, the analysis also sought to determine whether the cost living, housing and rental costs matched the amount a user recieves in benefit payments such as Universal Credit, Housing Allowance and several others.


Factor analysis was also conducted to reduce the number of variables in the predictive models used. Variables were narrowed down to 'size of monthly rent' and 'number of children per household'. 

The project is here:[UK Welfare State Analysis](https://github.com/JUA96/FRS-welfare-data-analysis)

### Other Projects

Some of my other projects have included:

- Social Media Analysis of the 2019 Democrat Presidential Primaries, using R.
- Predicting House prices using Bayesian methods
- Panel Data Analysis of the impact of Chinese Financial flows on state level governance in Africa.

Apps: 

- Using ``streamlit`` I built an geospatial app that be used to analyse car collisions across New York City. The app is [here](https://github.com/JUA96/streamlit-geospatial-app-python)

You can find the [remaining projects here in my repo](https://github.com/JUA96?tab=repositories)

Happy browsing! 😀
