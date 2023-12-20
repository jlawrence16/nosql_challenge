# nosql_challenge

In this project, I was tasked with evaluating Food Stanards Agency rating data of various dining establishments for the editors of a food magazine. 

This involved setting up a Mongo NoSQL database using mongoimport and Pymongo. The database was then updated with some new data and the format of some number values were then updated (using Pymongo).

The magazine had specific questions to be answered which meant using queries, fields, sorts and aggreations in Pymongo. Results were displayed and aslo exported to Pandas dataframes.

Question 1: Which establishments have a hygiene score equal to 20?
Question 2: Which establishments in London have a RatingValue greater than or equal to 4?
What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
Question 4: How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas
