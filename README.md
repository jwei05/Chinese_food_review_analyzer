# Chinese Food Review Analyzer

## Description
Given a food review in Chinese, the application outputs a list of good and bad dish names mentioned in the review, along with their English translations. 

## Dependencies
Python 3.6.5, numpy, pickle, keras, tensorflow, [jieba](https://github.com/fxsjy/jieba)

## How to Run
- cd into the directory

- run "jupyter notebook". After a broswer window is launched, open "Chinese food review analyzer.ipynb"

- To load the existing model, run the first cell in the notebook to load the dependencies, and then start running all the cells from the one with the title "Functions to load meta data and the model we just trained and saved".

- To train the model from beginning, ran the whose notebook top to bottom. 

- The instructions for running sample test reviews are included in the notebook. 

## Reference:
Various parts of the sentiment analysis, including the model architecture and text preprocessing techniques, are inspired by this project: https://github.com/Tony607/Chinese_sentiment_analysis
