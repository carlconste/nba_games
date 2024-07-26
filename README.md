# Generalized Linear Models & Non-Parametric Modeling and Bayesian Analysis on NBA Games Data

A Group final project for **DATA 102: Data, Inference, and Decisions**. Full project specifications can be found [here](https://drive.google.com/file/d/1cBz7raoqPeYcshWqv89KslZIOTfC91-F/view).

Our group chose to use the [NBA Games Dataset](https://www.kaggle.com/datasets/nathanlauga/nba-games) for our project. We were specifically interested in the following questions:
1. [Generalized Linear Models & Non-Parametric Modeling] Could we predict the win rate of a team for the upcoming season with incomplete data based on prior seasons' performances?
2. [Bayesian Analysis] How does the exposure of a team to a serious injury impact their scoring trends and performance?

For our first research question, we chose to use Ordinary Least Squares (OLS) as it would also give insight into which game statistics held the most importance when predicting win percentage. We also used a Random Forest Regressor for our Non-Parametric Model to minimize potential overfitting. After model fitting and parameter adjustment, we concluded that our Random Forest Regressor model could predict the win rate of a team with incomplete data due to it outperforming the OLS model.

For our second research question, we used Bayesian Hierarchical Modeling as we were missing data on how a team performs when exposed to an injury. From our model, we discovered that teams that experienced a serious injury had a higher amount of variation in their performance as opposed to teams that did not experience a serious injury. We concluded that a team sustaining a serious injury may disrupt their overall season performance and suggested implementing some solutions.

For our full report, analysis, and data gathered, please refer to the PDF inside this repo.

Date Completed: Fall 2023

---
Collaborators: **Emily Chin ('25, Data Science), Osmaan Mysorewala ('24, Data Science), Joshua Sengvongdeuane ('24, Data Science)**
