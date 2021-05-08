# DSCI 100 Project: Classification of Facebook Post Type Using Social Media Performance Metrics

The rapid advancement of technology has transformed the business world. Social media platforms have become the best place for businesses to advertise their brands by increasing customer engagement. This report focuses on the most popular social network worldwide, Facebook, with over 2.7 billion monthly active users. 

The dataset *Facebook performance metrics* contains data related to posts published throughout 2014 on a renowned cosmetics brand's Facebook page. Post information such as type (photo, status, link, or video), time posted (month, day, and hour), user engagement (comments, likes, and shares), impressions on each post, and whether the post was paid or unpaid is included in the dataset. 

This project uses 'post_consumptions', all relevant columns from this dataset to determine the type of a brand's Facebook post. We determine which of these metrics are relevant in our cleaning and exploration of the data. We use our chosen predictors to build a prediction model using the K-nearest neighbour classification algorithm, implemented in the `tidymodels` framework, to predict the type of a post (photo, status, link, or video).
