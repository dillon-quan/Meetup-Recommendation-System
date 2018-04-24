# Meetup-Recommendation-System


Summary
My second capstone project for springboard is my own attempt to create a recommendation system for Meetup.com. This social website allows user to join groups and participate in events hosted by groups of various categories to further explore and dab in the user interest. As a fellow user of Meetup.com, I have participated in a couple Data Science groups and attended a couple events. This project was inspired by the top contributors that queried this data using Meetup's API on kaggle. The link to their GitHub Repo can be found down below. This project is my attempt to develop a recommendation system of my own using the data these users posted on Kaggle.

Top Contributors on Kaggle on this dataset Github: https://github.com/sumit-code/MSCA-31005-database-class-project

Dataset
The dataset was retrieved from Kaggle that contain various tables regarding members, groups, events, and location. The data here only consist of three major city: San Francisco, New York City, Chicago. Refer to the link to further explore the dataset.

Here is the link to the dataset used for this project. https://www.kaggle.com/sirpunch/meetups-data-from-meetupcom

Approach
The approach to this problem will be to use collaborative filtering to recommend users other groups that they may find intrest in using matrix factorization. As this dataset has implicit ratings, further research will be needed to begin. The idea is to recommend users groups to join based on similar users or similar items that share the same preferences or similar to the user taste in some way. 

Extension
Further queries can be made using Meetup's API to gather more data to recommend events to users based on the groups they are in.
