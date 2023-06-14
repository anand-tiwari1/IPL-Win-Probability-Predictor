# IPL-Win-Probability-Prediction

### Introduction
A webapp using Python, Machine learning algorithm  and Streamlit for Predicting the winning probability of each team.

https://github.com/anand-tiwari1/IPL-Win-Probabilty-Prediction/assets/88627473/46f445c5-131a-4e43-801b-af51eb014eb5

### Description of Data needed
- Name of the Batting Team in second inning
- Name of the Bowling Team in the second inning
- Target Score of the first inning
- Current score
- Overs completed
- Wickets Gone till now

Given these inputs the web app can predict the probability of winning for both the teams.
This is well trained model which takes in account the rivalary of the teams, past performances against each other, outcome of the match with some similar situations in the past.
This model studied the dataset of each match and each ball delivered in all of those matches from last 11 years. 

If you want to use the webapp:
1. Download the dataset from here https://www.kaggle.com/datasets/ramjidoolla/ipl-data-set
2. Run 'IPL Win Predictor.ipynb' to create model
3. Run 'app.py' to run the webapp
