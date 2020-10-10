# Recommendations With IBM
## Project Description

This project as part of a Udacity course. The source data is from IBM watson users and their interactions with articles.  The aim of this project is to analyze these interactions that users have with articles and make recommendations of new articles that they might like.

## Files 
Recommendations_with_IBM.ipynb is jupyter notebook with all the code.
Recommendations_with_IBM.html is html version of the file.
The data files needed are in the /data directory.
project_tests.py is used for validations.


### I. Exploratory Data Analysis
This section is used  to explore the data  before diving into the details of  recommendation system in the later sections.

### II. Rank Based Recommendations
We first find the most popular articles simply based on the most interactions. These are  the articles we might recommend to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering
Here we  look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This is step in the right direction towards more personal recommendations for the users. 

### IV. Content Based Recommendations (EXTRA - NOT REQUIRED)
Would have been interesting to implement at a later time.

### V. Matrix Factorization
Using the user-item interactions a matrix decomposition is built. Using your decomposition, we see how well we predict new articles an individual might interact with.