---
title: "Customer Churn Prediction Model"
excerpt: "This project develops a predictive model to identify early signs of customer churn at a popular UK grocery store chain, using deep learning techniques on historical transaction data. By analyzing patterns of customer engagement, the model forecasts future purchase behaviors and identifies potential churn risks, allowing proactive retention strategies to be implemented effectively. <br/><img src='/images/rnn.png'>"
collection: portfolio
---

This project focuses on developing a predictive system to preemptively identify signs of customer churn within a grocery store's sales and marketing department. Traditional methods 
engage customers reactively, often failing to reclaim them after disengagement. To address this, the project involves analyzing Tesco's transaction data from December 2009 to 
December 2011 to identify patterns that suggest a reduction in shopping activity, which could indicate potential churn. The goal is to detect customers who show signs of reduced 
engagement, such as not making purchases over two consecutive months.

I created a deep learning model using a Recurrent Neural Network (RNN) architecture with Long Short-Term Memory (LSTM) units to forecast customer purchase patterns over time. 
These forecasts are then used to normalise predictions between 0 and 1, interpreting them as churn probabilities. The model processes historical transaction data to recognise 
patterns and predict future activities, thus allowing early intervention strategies aimed at improving customer retention. This preemptive approach leverages detailed customer 
behavior analytics to mitigate the risk of churn by engaging customers before they disengage completely. The code for this project can be found [here](https://github.com/GiuseppeIncardona9/Data-Driven-Projects/blob/main/Customer%20Churn%20Prediction/Customer%20Churn%20Prediction%20Model.ipynb)
