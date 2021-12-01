## AA_Classification_Modelling_Project

## Description:

I was given a dataset (bbc-text.csv) consists of 2225 documents from the BBC news website corresponding to stories in five topical areas from 2004-2005.  <br>
The csv file consists of two columns, first being the “category”, which are the labels for each document: business, entertainment, politics, sport, and tech. Second column is “text”, which is the BBC news stories/ Document. 

The goal to preprocess and transform the data into either bag-of-words or TF-IDF matrix, then fit the data into various classification models to classify the BBC news stories into different categories and lastly, comparing the performance of each model.  <br>

To tackle this problem, I have broken down it into four steps and will explain each step with details in the later part of this report.  <br>
The first step will be text data pre-processing. Started off by extracting the data from the csv file and store it inside a data frame, followed by data cleansing using proper techniques such as removing stop words, stemming and lemmatizing.  <br>

And lastly, the cleansed text data will be transformed into bag of words or TF-IDF matrix for classification modelling later.  <br>
For step 2, it will be text data understanding, first by extracting the keywords from each document using TF-IDF matrix, the keywords extracted can be then used for analysis using Association Rule Mining.  <br>

The goal is to visualize and understand the associations between the keywords by category or by overall documents.   <br>

For step 3, it aims to use classification modellings on bag-of-word or TF-IDF matrix to classify the BBC news stories into different categories.  <br>

And to evaluate the models performance using testing data and further improve the model performance by tuning model hyperparameters or further cleanse or transform the text data. The last step is to summarize the findings, which can be a collection of accuracy scores from different models using either bag-of-word or TF-IDF matrix and choose the most suitable model to use to classify future data. And finally, some possible improvements to be made. <br>

 

## Features 
### Existing Features

## Technologies Used

