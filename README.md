# Predicting the Outcome of a League of Legends Game

This project aims to predict the outcome of a League of Legends (LoL) game based on the first ten minutes of gameplay. Using various machine learning models, we analyze key in-game metrics to determine if the "blue" team will win the game. The dataset used includes detailed performance data for both teams within the first ten minutes of gameplay.

## Introduction

In League of Legends, the first ten minutes of the game are crucial for setting up the rest of the match. In this project, we aim to build machine learning models that predict whether the blue team will win based on early-game performance. This project applies various models including Logistic Regression, LDA, K-Nearest Neighbors, and Elastic Net to predict the outcome.

## Dataset

The dataset is sourced from Kaggle: [League of Legends Diamond Ranked Games (10 min)](https://www.kaggle.com/datasets/bobbyscience/league-of-legends-diamond-ranked-games-10-min).

- **Data file**: `high_diamond_ranked_10min.csv`
- **Codebook**: `high_diamond_ranked_10min_codebook.txt`

Both the data file and codebook can be found in this repository.

## Features

The key features in this dataset include:
- **Wards Placed**: Number of wards placed by the blue team.
- **Kills/Deaths/Assists**: Performance stats for the blue team.
- **Gold/Experience**: Total gold and experience gained by the blue team.
- **Elite Monsters**: Number of elite monsters (Herald, Dragon) killed.
- **Towers Destroyed**: Number of towers destroyed by the blue team.

## Usage

The original project is an HTML file which can be viewed [here](https://drive.google.com/file/d/17WbG3SM3lLllVCqy-pikxrMVwO7zKBi6/view?usp=sharing)

## Models
This project implements the following models:

Logistic Regression: A basic classifier for predicting the game outcome.
Linear Discriminant Analysis (LDA): For classification based on linear combinations of the predictors.
K-Nearest Neighbors (KNN): A non-parametric method used for classification.
Elastic Net: A regularized regression method, which combines Lasso and Ridge penalties.

## Results
The best performing model was the Elastic Net model, which achieved a ROC AUC of approximately 0.81 on the test set. Key findings indicate that gold and experience advantage in the early game are critical factors for determining whether the blue team wins.

## License
