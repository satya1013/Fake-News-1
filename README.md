# Fake-News-Detection 
B.Tech Final Year Project on Fake News Detection (IIIT-R).

The purpose of this project is to conduct analysis on certain textual data which is extracted from various articles and conclude the judgement of whether the data is fake or real, with the goal of mitgating the spread of fake news.
## Dataset source 
The dataset is downloaded from kaggle which is used in a fake-news-detectin competition. it contains extraxts of various articles and their label of real or not.
## Project Overview
The analysis consists of two stages:
   - Exploratory Data Analysis. The detailed notebook is found in notebooks folder
   - Machine Learning Modeling. The detailed notebook is found in notebooks folder

Machine Learning models used:
  1. RNN
  2. RNN-CNN
  3. RNN with attention 
  4. Transfrmer model- XLM-ROBERTA
## Model Comparison 
The first experiment wiht reccurrent neural network gives accuracy around 0.85.later,all the models tried, did increase the efficiency and we ended up having our beest result of 0.94 with transformer model
## Limitations
Best model Transformmer can only detect 94% of default.
Models seem to be suffering with slight overfitting
Used only 30,000 records.
## Future Work
Get more computational resources to tune RNN parameters.
modify model architecture.
