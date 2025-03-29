# Recommender-systems-online-courses

## Objective

We consider data about online courses and user interations with the courses. The objective of this notebook is to create a small survey of recommender systems to understand the main ideas behind contert-base filtering and collaborative filtering.

This work is based on the Machine Learning Capstone Project at https://www.coursera.org/learn/machine-learning-capstone?specialization=ibm-machine-learning


## About the data

Course_df:
contains the courses id's, names and the genres of the courses in sparse matrix form
available at 
course_genre_url = "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-ML321EN-SkillsNetwork/labs/datasets/course_genre.csv"

ratings_df:
contains user id's , courses taken, and the rating given to each course taken.
available at
ratings_url = "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-ML0321EN-Coursera/labs/v2/module_3/ratings.csv"

course_content_df:
contains course id, title of the course, and a description of the course.
available at
course_url = "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-ML321EN-SkillsNetwork/labs/datasets/course_processed.csv"
