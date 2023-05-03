# Sentiment_Analysis
**Sentiment analysis:** Classified sentiments into positive, negative, or neutral categories using the Naive Bayes Algorithm. 
Problem Solved in this Project and How it is Solved:
Human express thier emotions/ sentiments on social media about almost everything on platforms like twitter, facebook, yelp, reddit. The problem is the abundance of data present which can not be handled by humans alone.

This is when the term big data got its foundation. To handle the big data we need Machine learning. the problem is computers only understand numbers not text or sentiments.

Thanks to machine learning liabraries of Python it is now possible to convert text to a form which can be understood by the computer.

In simple words we clean the text, process it by removing stopwords, punctuation, special characters and then train our ML model to perform sentiment analysis.

It is similar to how we train a student by teaching the content of the class then testing it to check how accurate it got trained. The more content is taught to the student the better score it acquires. similarly the more data we feed to our maching learning model the better it gets at prediction.

**Project Name:** Sentiment Analysis on Movie Reviews
**What is sentiment analysis?**
Sentiment analysis is a method in machine learning that uses natural language processing in order to analyze text or speech and interpret subjective information into qualitative data. Oftentimes, it is used to interpret opinionated text, and sort them into positive, negative, or neutral categories.

**Why it is important?**
Sentiment analysis is extremely useful in the age of big data where we have enormous amounts of data at hand. People express their sentiments on social media. The ability to monitor, obtain an overview of the wider public opinion and the extracting meaningful insight from it can be beneficial in every organization. Be it Politics, marketing or entertainment industries. For example: In entertainment industry doing sentiment analysis on publics reviews on a movie can help the film makers find out which movies get positive feedback which can help them in coming up with better and profitable content in the future.

**Naive Bayes Algorithm**
The Naive Bayes Algorithm is a classification algorithm that is used to predict class based on certain attributes. In this case with sentiment analysis, it predicts the opinion of text based on certain keywords and phrases in order to classify them as positive, negative, or neutral. It is one of the fastest and most efficient algorithms used to process and interpret large amounts of data.

There are three types of Naive Bayes model under the scikit-learn library:

**Gaussian:** used in classification and it assumes that features follow a normal distribution.

Multinomial: It is used for discrete counts. For example, let’s say, we have a text classification problem. Here we can consider Bernoulli trials which is one step further and instead of “word occurring in the document”, we have “count how often word occurs in the document”, you can think of it as “number of times outcome number x_i is observed over the n trials”.

**Bernoulli:** The binomial model is useful if your feature vectors are binary (i.e. zeros and ones). One application would be text classification with ‘bag of words’ model where the 1s & 0s are “word occurs in the document” and “word does not occur in the document” respectively.

https://www.analyticsvidhya.com/blog/2017/09/naive-bayes-explained/#:~:text=Naive%20Bayes%20Model-,What%20is%20Naive%20Bayes%20algorithm%3F,presence%20of%20any%20other%20feature.

Libraries used
Pandas, Numpy, Matplotlib, Sklearn, NLTK

Project Introduction
For our project, we decided to use sentiment analysis to create a program in which we will build a model and then train it with 75% of the dataset and then will test it using the remaining data set. We will check the accuracy of our model to predict sentiments.

**Data set being used**
IMDB Dataset of 50K Movie Reviews https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?select=IMDB+Dataset.csv

**Steps:**
Text preprocessing Removing null values Remove html tags Removing stop words Converting to lower case Removing special characters stemming Text vectorizing using countvectorizer Split the data for training and testing Feed the data Train and test Deployment
