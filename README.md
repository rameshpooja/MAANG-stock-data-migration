# MAANG-stock-data-migration

This dataset includes the historical data of stock prices for MAANG companies. It contains the daily, weekly, and monthly stock prices for each company, and they are automatically updated daily. This dataset has 15 datasets, and each file has around 7 columns. Here we have daily, monthly, and weekly data for each of the companies from the years 2000 -2023. http://www.kaggle.com/datasets/nikhil1e9/ne8lix-stock- price/

Adopted py scripts for daily, weekly, and monthly to transform and insert the 15 files into cloud Postgres. Here, used the Kaggle API instead of downloading the 15 files into the local or cloud bucket, as the data is very dynamic and changes daily . Using a cloud scheduler to trigger the cloud functions.
