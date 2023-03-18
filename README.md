# Sentiment-Analysis-classification-and-Rating-Predictions
This repository has three projects related to social media. 
* The First project, 'GuviCourses_Rating_Prediction', is focused on helping the Guvi company predict the ratings that their courses will get from learners. By doing so, the company can identify areas where improvements are needed to enhance the overall learning experience for their learners.

* The Second project, 'Twitter Sentiment Analysis', is focused on assisting users in determining whether a given tweet is positive or negative. This can be particularly useful for businesses or individuals who want to monitor public sentiment about their brand or a particular topic.

* Finally, the 'Instagram Influencers' project consists of a series of questions that can help
improve various data processing techniques.

Overall, this repository provides a valuable resource for anyone interested in exploring the intersection of social media and data analytics. Each project offers unique insights and tools for analyzing and optimizing your social media strategy.

# 1)GuviCourses_Rating_Prediction

 Goal of this project is to predict the ratings given by the
learners to the course based  on various factors like price, number of suscribers, number of reviews, 
course subject, content duration

## WorkFlow of Project:
   ```bash
1) Importing Libraries And Loading Dataset:
```
  Importing Necessary libraries to load dataset. 
```bash
2) Data Preprocessing:
```
*  Overcoming Null values
*  Removing Noise data/Feature
*  Label Encoding
*  Handling skewness
*  Handling Outliers
 
 All these process are done in Preprocessing of data and analysed.

```bash
3) Exploratory data Analysis:
```
  The relationship between Rating and specific Features are analysed by plotting scatterplots.

```bash
4) Model Building, Training and Testing
```
  Now Model is build and Fit to the dataset and trained with training data and get tested.

```bash
6) Evaluating Model:
``` 
  Finally Model is Evaluated. My model gives 42 % due to high Multi Collinearity.
  

# 2) Twitter Sentiment Analysis

* This project is focused on assisting users in determining whether a given tweet is positive or negative. 
* This can be particularly useful for businesses or individuals who want to monitor public sentiment about their brand or a particular topic.



## WorkFlow of Project:
   ```bash
1) Importing Libraries And Loading Dataset:
```
  Importing Necessary libraries to load dataset. 
```bash
2) Preprocessing The Dataset:
```
   Next step is preprocessing the dataset like removing url's, Punctuations, Stopwords,and lemmetizing the data to get root word
```bash
3) Exploratory Data Analysis:
```
*  Handling Outliers,Handling skewness,Handling 
   Then Analysing the data by plotting Most Frequent Words and Hashtags in the tweet in positive tweets and Negative tweets

```bash
4) Feature Extraction:
```
   Next is extracting Features and converting the string/object Datatype Tweets into Float Matrix/Vector by tfidf Vectorizer

```bash
5) Model Building, Training and Testing
```
  Now Model is build and Fit to the dataset and trained with training data and get tested.

```bash
6) Evaluating Model:
``` 
  Finally Model is Evaluated. My model gives 75 %
  
## 3) Instagram Influencers 

This project focused majorly in Data Preprocessing and EDA Of Instagram Influencers Dataset.
