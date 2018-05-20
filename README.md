# Meetup-Recommendation-System


### Summary

My second capstone project for springboard is my own attempt to create a recommendation system for Meetup.com. This social website allows user to join groups and participate in events hosted by groups of various categories to further explore and dab in the user interest. As a fellow user of Meetup.com, I have participated in a couple Data Science groups and attended a couple events. This project was inspired by the top contributors that queried this data using Meetup's API on kaggle. The link to their GitHub Repo can be found down below. This project is my attempt to develop a recommendation system of my own using the data these users posted on Kaggle.

Top Contributors on Kaggle for this dataset: https://github.com/sumit-code/MSCA-31005-database-class-project

### Dataset

The dataset was retrieved from Kaggle that contain various tables regarding members, groups, events, and location. The data here only consist of three major city: San Francisco, New York City, Chicago. Refer to the link to further explore the dataset.

Here is the link to the dataset used for this project. https://www.kaggle.com/sirpunch/meetups-data-from-meetupcom

### Approach

Recommendation System has two major approach, content-based and collaborative filtering. Content-based focuses on using features that characterizes the item and find similar items that resemble previous like items and recommend similar items to the user. Collaborative filtering deviates from this characterization and finds a neighborhood of similar users or items and recommends user items that has not been considered by the user. There are many ways to attempt collaborative filtering. Memory-based or model-based are all part of collaborarive filtering. All of these methods will be explored.

### Extension

Further queries can be made using Meetup's API to gather more data to recommend events to users based on the groups they are in.
