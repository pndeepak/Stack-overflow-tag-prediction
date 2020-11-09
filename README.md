<h1><b><center> Stackoverflow tag  prediction </center></b></h1>

<img src="https://wizardsourcer.com/wp-content/uploads/2019/03/Stackoverflow.png">
<a href="https://colab.research.google.com/drive/1_fd9IX_qoKOuMVUn7zBpvKCFjyyT0gZF" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


## Problem Description
Stack Overflow is the largest, most trusted online community for developers to learn, share their programming knowledge, and build their careers.

Stack Overflow is something which every programmer use one way or another. Each month, over 50 million developers come to Stack Overflow to learn, share their knowledge, and build their careers. It features questions and answers on a wide range of topics in computer programming. The website serves as a platform for users to ask and answer questions, and, through membership and active participation, to vote questions and answers up or down and edit questions and answers in a fashion similar to a wiki or Digg. As of April 2014 Stack Overflow has over 4,000,000 registered users, and it exceeded 10,000,000 questions in late August 2015. Based on the type of tags assigned to questions, the top eight most discussed topics on the site are: Java, JavaScript, C#, PHP, Android, jQuery, Python and HTML.

**Problem Statemtent**

Suggest the tags based on the content that was there in the question posted on Stackoverflow.

**Source:** https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/

## Overview
This is a multilabel classification problem implemented using OneVsRestClassifier for 500 different tags. Since Logistic regression using SGD converges faster we have used it as a base estimator for our OneVsRestClassifier. The performance metric used to monitor model performance is micro-F1 score.


## Notebook contents
- Problem description
- Problem overview
- Exploratory data analysis
- Machine Learning models
- Comparison of various ML models

## Algorithms used
- OnevsRestClassifier 
- Logistic regression (using SGD)
- SVM (using SGD)

## Tools and technologies used
![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=170>](https://scikit-learn.org/stable/) [<img target="_blank" src="https://clay-atlas.com/wp-content/uploads/2019/08/python_nltk.png" width=180 height=100>](https://www.nltk.org/) [<img target="_blank" src="https://miro.medium.com/max/1400/1*7oukapIBInsovpHkQB3QZg.jpeg" width=200>](https://colab.research.google.com/) 
