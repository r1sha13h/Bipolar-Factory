# Bipolar-Factory
Kindly refer my resume : https://drive.google.com/file/d/1ulgaOA2cN2JwPELb1UB9kW0uJKKttatk/view?usp=sharing
# Theory
Virality : virality has varied number of meanings and virality of facebook post depends on various number of factors. Here i have tried to define virality as number of times a news post has been shared by the users. 

I have used factors such as 
-> time duration (since posted) 
-> Number of likes and comments
-> text in the news post 
-> Presence of an Image on the post
-> Channel on which the post has been made

I have scraped data from following news channels : 
BBC news, 
CNN, 
New York Times, 
Fox News, 
ABC News, 
Huffington Post, 
NBC News, 
Time, 
Daily Mail, 
Business Insider, 
Now This News, 
Al Jazeera

# ML Models

All The above have been used to predict number of shares made on that post (virality) using regression models such as : 
Linear Regression, 
SVR, 
Random Forest

However , above models have failed to perform accuratrly on the given data and therefore i used : DNN
DNN is able to provide a fairly high accuracy (over 80%)

# Steps to follow

1. Execute collect_data.py - scrapes news from facebook pages of popular News companies, processs it and converts the data in .csv format, **you dont need to execute this file** as .csv file is available directly to us for analysis.

2. Execute virality_predictor.py - Predicts number of shares of news post on a FB page and compares it with actual number of shares. It directly accesses the new.csv file that was created after scraping FB news pages. **You only need to execute this**.

3. Data is present in news.csv file
