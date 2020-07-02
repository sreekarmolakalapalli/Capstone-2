# Capstone-2

In this project we develop a BERT-based NLP  model that is trained on Coachella 2015 twitter data from Crowdflower.

## EDA

The EDA.ipynb file cleans our tweet text data and exports it to the clean_coachella.csv file.

## Data Pre-processing & Modeling

This file prepares our data to be loaded into the BERT model, trains the model, and then calls the Twitter API to predict the sentiment of recent tweets regarding an upcoming music festival.

## Pretrained Pipeline

We use a Transformers pretrained sentiment analyis pipeline to predict on our twitter data which we then compare to the performance of our model.
