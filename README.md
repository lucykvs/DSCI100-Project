# Data Science Project: Classification of Facebook Post Type Using Social Media Performance Metrics

This project was completed for the undergraduate data science course at **UBC**. This course gives an intensive introduction to **R** using **JupyterLab**.

The rapid advancement of technology has transformed the business world. Social media platforms have become the best place for businesses to advertise their brands by increasing customer engagement. This report focuses on the most popular social network worldwide, Facebook, with over 2.7 billion monthly active users. 

The dataset *Facebook performance metrics* contains data related to posts published throughout 2014 on a renowned cosmetics brand's Facebook page. Post information such as type (photo, status, link, or video), time posted (month, day, and hour), user engagement (comments, likes, and shares), impressions on each post, and whether the post was paid or unpaid is included in the dataset. 

This project uses the columns `lifetime post consumptions`, `lifetime post reach by people who like page`, and `lifetime people who have liked page and engaged with post` from the dataset, along with the generated columns `like ratio`, `share ratio`, and `engagement ratio`, to determine the type of a brand's Facebook post. The relevance of these metrics was determined through **cleaning and exploration of the data**. The chosen predictors were used to build a **prediction model** using the **K-nearest neighbours classification algorithm**, implemented in the `tidymodels` framework, to predict the type of a post (photo, status, link, or video).
