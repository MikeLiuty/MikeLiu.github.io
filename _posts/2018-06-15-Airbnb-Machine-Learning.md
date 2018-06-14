---
layout:     post
title:      Review and thoughts of "Using Machine Learning to Predict Value of Homes On Airbnb"
date:       2018-01-20 22:20:15
summary:    A introduction of Merge Sort
categories: New Area
---

Because of the recent project in the company involved with machine learning method need, so I read some research about it. Ideally, I need to design a project to make simple prediction of housing prices. After reading the article, I improved my understanding of machine learning.

Some new words:
LTV: Customer Lifetime Value

Process:
Feature Engineering: Define relevant features
Prototyping and Training: Train a model prototype
Model Selection & Validation: Perform model selection and tuning
Productionization: Take the selected model prototype to production

Airbnb developed Zipline to define features and attribute which can influence the price of housing, which contains more than 150 attributes.

Then, they used Scikit-Learn and Spark to design the model.

And, compare the RMSE to decide which design is the best.
(The root-mean-square error (RMSE) is a frequently used measure of the differences between values (sample and population values) predicted by a model and the values actually observed.)

And last, develope the project.

Reference:

https://medium.com/airbnb-engineering/using-machine-learning-to-predict-value-of-homes-on-airbnb-9272d3d4739d
