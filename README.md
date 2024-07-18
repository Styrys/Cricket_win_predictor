# Cricket_win_predictor

This repository contains ML model used to predict a cricket match victor in T20 series based on curated dataset spanning across seasons 2007-17, picked from Kaggle.

Preliminary features chosen for the predictions are:
 - Toss feature (Does winning toss affect victory)
 - Venue (Gauges team performances on specific locations)
 - Weather (How Duckworth-Lewis method affects matches, how climate conditions affect team performance, etc.)
 - Player of the Match (Does superlative individual performance supercede team performance in affecting victory)

The list of models used for predictions:
 - Naive-Bayes Algorithm
 - Decision Tree Regression
 - Support Vector Classifier
 - Random Forest Model

Confusion matrices were drawn for each model used for prediction, and the accuracies were compared to determine which model(s) to use for further finetuning the prediction process.
