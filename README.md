# Subreddit-Gaming
The goal of this project is to create a model using features in datasets extracted from the /r/gaming subreddit to predict the score of a comment.

# The Data
The comments data was extracted from a Google BigQuery database, https://bigquery.cloud.google.com/table/fh-bigquery:reddit_comments.2018_05?pli=1 , using SQL commands.  The data comes from May 2018 and has been limited to entries originating from the /r/gaming subreddit.  

The posts data was also extracted from a Google BigQuery database, https://bigquery.cloud.google.com/table/fh-bigquery:reddit_posts.2018_05?pli=1 .  The data also comes from May 2018, restricted to just the /r/gaming subreddit.  
