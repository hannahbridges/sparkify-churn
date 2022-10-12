# Sparkify Churn - Capstone Project

## Project Motivation
This project uses event log data from user interactions with Sparkify, a fictional music streaming service, to predict User Churn.
This is a binary classification problem aiming to predict which users will cancel their subscription so that Sparkify can attempt to provide offers or discounts to encourage them to stay.

The project is divided into 3 main parts:
1. Data cleaning and exploration
2. Feature engineering to create a user level modelling dataset
3. ML pipeline to train binary classifiers with grid search and select the best model for this task

## Dependencies
Python 3.5+
Libraries: NumPy, Pandas, Seaborn, Matplotlib
PySpark 3.1.2

## Installing
To clone the git repository:
git clone https://github.com/hannahbridges/sparkify-churn.git

## Files
sparkify-churn.ipynb contains all code needed to run this project including data exploration, feature engineering and modelling.
The dataset can be downloaded from https://video.udacity-data.com/topher/2018/December/5c1d6681_medium-sparkify-event-data/medium-sparkify-event-data.json

## Results
The findings of this analysis are described in a blogpost [here](https://medium.com/@hannahbridges1/churn-or-no-churn-a-sparkify-challenge-8e392cb6f7fc).  

## Licensing, Authors, Acknowledgements, etc.
Thanks to Udacity for providing the dataset used in this project and running the Data Scientist nanodegree.