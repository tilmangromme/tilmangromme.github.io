---
title: Regular Update
author: tilmangromme
date: 2025-05-19 13:11:00 +0800
categories: [Blogging, Software Development, Machine Leaerning]
tags: [Software, ML, SWE]
render_with_liquid: false
---

I created a new folder in the supplyplansolver directory called ml_regression_process. As you could tell, here we will be doing experiments and doing some exploratory analysis on the implementation of machine learning features that we would like to include on our product. I pulled a test dataset from our test data generator in the directory sp_data_generator. The datasets generated here are a rough representation of what might be seen in industry. The implementation of the machine learning process occured in a Jupyter .ipynb file for ease of use and experimentation. I reaquanted myself with some of the strategies in preparation of a dataset, such as data cleaning, feature engineering, feature extraction and the creation of thorough and meaningful visualizations. I fed the manipulated dataset to an XGBoost Regression model as this model is robust and popular in industry. The model performed poorly when fed testing data which opens up more avenues for experimentation to try to create useful models. I am doing some additional research about enterprise machine learning applications and will hopefully come back with some meaningful insights that I will relay to the blog on my next post.