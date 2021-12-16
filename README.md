# Covid19 Tweets Analysis

## Overview of the project
This project focuses on exploring specific tweets and implementing sentiment analysis.

## Resources
- Data: [covid19_tweets.csv](https://github.com/Takomochi/Covid19_Tweets_Analysis/blob/main/Resources/covid19_tweets.csv)
- Software: Python 3.7.10, Visual Studio Code

## About Data
These tweets are collected using Twitter API and a Python script. A query for this high-frequency hashtag (#covid19) is run on a daily basis for a certain time period, to collect a larger number of tweets samples. 

The tweets have #covid19 hashtag. Collection started on 25/7/2020, with an initial 17k batch and will continue on a daily basis. (Kaggle)

## Results


### 1. Tweets locations

As we can see, large number of tweets are from India and United States with more than 7000 tweets.

<img src="https://user-images.githubusercontent.com/85041697/146387914-89e0d81d-6558-4a08-b9b5-5b4d6fa52313.png" width=600>


### 2. Number of tweets timeline
Number of tweets shows not so much difference but July 25, 2020 had a significant number of tweets compare to other days.

<img src="https://user-images.githubusercontent.com/85041697/146388442-570a884c-956a-497e-bd09-bc77aabff67c.png" width=600 height=400>


### 3. Verified & Non-verified users

In the dataset, about 13% of users are verified users.

<img src="https://user-images.githubusercontent.com/85041697/146389307-dc58258b-91d5-4910-92d3-ae9e3941892d.png">

Is there any relationship between verified users and number of followers, friends, and favorites? There is a strong correlation between verified user and followers as we can expect.

<img src="https://user-images.githubusercontent.com/85041697/146390565-08624e65-f5a5-45c1-bf06-ce36d830805f.png">


### 4. Word Clouds

Made word cloud for all the texts, texts from India and texts from United States.
As we can expect, all of them has COVID19 and coronavirus as key words.

In India word cloud, there are words like "Economy", "Election", and some city names. In United States, there are words like "DonaldTrump", "death", and "Mask".

**Global** <br>
<img src="https://user-images.githubusercontent.com/85041697/146391428-1fd336e4-c564-45e0-b1d6-e09cbe8cd403.png">

**India** <br>
<img src="https://user-images.githubusercontent.com/85041697/146391811-ff6ae09d-daa7-432d-a2c3-ccba201908db.png">

**United States** <br>
<img src="https://user-images.githubusercontent.com/85041697/146391993-d353700c-0f48-4622-bf6f-f6a657079013.png">
