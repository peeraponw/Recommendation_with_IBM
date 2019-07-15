# Recommendation_with_IBM
A part of Data Scientist Nanodegree program. This project creates a recommendation system in collaboration with IBM. The data is taken from the interactions between users and articles in IBM Watson Studio platform. This project aims to recommends users relevant articles to their history.

# Requirements
The notebook in this repo require only the following packages:
- pandas 0.24.2
- numpy 1.16.3
- matplotlib 3.0.3
# Summary
This project starts by exploring the data. The dataset composes of two files: `user-item-interactions` and `articles_community`. The `user-item-interactions` includes `article_id`, `title`, and `email` columns. The `articles_community` contains `doc_body`, `doc_description`, `doc_full_name`, `doc_status`, and `article_id` columns. In this analysis, the `articles_community` will not be taken into account. After data cleaning process, this notebook will take you to simple recommendation systems, i.e., rank based system, user-user based collaboration filtering, and SVD method.
