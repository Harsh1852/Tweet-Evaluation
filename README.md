# Tweet Evaluation Project

## Overview
This project develops a machine-learning-based system to analyze tweets from social media platforms like X (formerly Twitter). The system classifies sentiments into positive, neutral, or negative categories and predicts the potential virality (in terms of engagement) of tweets based on intrinsic characteristics. The project utilizes a variety of models, including XGBoost, LSTM, and VADER, to achieve its objectives.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Result](#result)

## Installation
- Clone the GitHub repository and install the required dependencies
  ```bash
  git clone https://github.com/Harsh1852/Tweet-Evaluation.git
  cd Tweet-Evaluation
  pip install -r requirements.txt
  ```
- Run the main script.

## Dataset
Multiple datasets are used in this project, containing columns like the content of the tweet, timing when the post waas made, hashtags used, number of likes, shares, and comments, along with the sentiment expressed in the posts.

## Methodology
- The data is preprocessed by cleaning it to only have tweets or posts made on X and noise removal is done.
- The feature for sentiment analysis of the post is also updated as inconsistencies can be found in them. 
- We develop several ML models, including XGBoost, LSTM for the prediction of the virality, and VADER for quick sentiment analysis.
- At last, feature engineering is performed on the dataset to extract features like Text-based features using TF-IDF.

## Result
The models were evaluated based on accuracy and F1-score among which XGBoost performed best in terms of accuracy of 86.03 % and F1-score of 0.78 for the virality prediction.
