# Customer-Lifetime-valuation-prediction-model

We invest in customers (acquisition costs, offline ads, promotions, discounts & etc.) to generate revenue and be profitable. Naturally, these actions make some customers super valuable in terms of lifetime value but there are always some customers who pull down the profitability. We need to identify these behavior patterns, segment customers and act accordingly. Calculating Lifetime Value is the easy part. First we need to select a time window. It can be anything like 3, 6, 12, 24 months. By the equation below, we can have Lifetime Value for each customer in that specific time window:

Lifetime Value: Total Gross Revenue - Total Cost

This equation now gives us the historical lifetime value. If we see some customers having very high negative lifetime value historically, it could be too late to take an action.

We are going to build a simple machine learning model that predicts our customers lifetime value.

Lifetime Value Prediction
Define an appropriate time frame for Customer Lifetime Value calculation
Identify the features we are going to use to predict future and create them
Calculate lifetime value (LTV) for training the machine learning model
Build and run the machine learning model
Check if the model is useful
