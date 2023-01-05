# ChatGPT-Data-Analysis

The data is a collection of tweets from Twitter with the hashtag - chatgpt. The tweets include discussion about chatgpt, sharing their experience, and asking questions. Overall, a collection of tweets surrounding ChatGPT. I built an ETL pipeline and did some data analysis. 
This repository has 2 files. One is the Jupyter Notebook file that has the code and the other is the CSV file.

Process: 

Firstly, ingesting the data using Spark.

Cleaning the data that is making sure there are no null values.

Now comes the data analysis which includes answering some questions about which user has the highest number of followers, types of device users, how many people have tweeted from a particular place, etc using Spark data frame as well as Spark SQL.

The transformed data is then loaded into the Postgres DB using the JDBC connection.

