# Thesis-Project
Topic of my thesis project:  

Generating a network of subreddits and users, with the aim of identifying communities, computing PageRank scores and being able to incorporate such information when developing a recommendation system.

The dataset folder contains the 100 csv files, each file represents a subreddit and it contains around 1000 rows.

There are 3 notebooks:
  - One is used for data collection using reddit's API
  - The second notebook contains the 1st part of the project code, which is creating the network graph & performing community detection
  - The third notebook contains the 2nd part of the project code, which is implementing user-item recommendation system (community/no community) using spark's ALS models.
    - The aim here is to observe whether a community-based recommendation system leads to more accurate recommendations than a general one. Another observation is to compare user influence within the community and across the network and see whether there is an effect on the recommendations or not.

Finally, there are 3 other files, subreddits categories csv file, graph Gephi file & another csv file containing the overall dataframe.
