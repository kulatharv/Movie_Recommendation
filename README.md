# Movie Recommendation System using Collaborative Filtering
- Project Overview

The Movie Recommendation System is designed to suggest movies to users based on their interests by analyzing historical user rating data. This project uses collaborative filtering, a popular recommendation technique that identifies similarities between movies based on user preferences.

The system helps users discover movies similar to the ones they already like and demonstrates the practical application of data analysis and machine learning concepts using Python.

- Objectives

    - Build a movie recommendation system using real-world rating data

    - Apply collaborative filtering techniques to identify similar movies

    - Reduce recommendation bias caused by insufficient data

    - Provide accurate and meaningful movie suggestions


Methodology

This project follows an Item-Based Collaborative Filtering approach:

1. Data Loading
        Load movie titles and user rating datasets
2. Data Preprocessing
        Merge movie titles with user ratings
        Handle missing values
2. Exploratory Data Analysis
        Analyze rating distribution
        Identify most-rated movies
4. Similarity Computation
        Create a user–movie rating matrix
        Compute similarity using Pearson correlation
5. Bias Reduction
         Filter movies with low rating counts
6. Recommendation Generation
         Recommend movies similar to a selected movie

Technologies Used
      Python
      Pandas
      NumPy
      Jupyter Notebook
      Collaborative Filtering
      Correlation Analysis

Results
      Successfully generated relevant movie recommendations
      Improved recommendation accuracy by filtering low-rated movies
      Demonstrated strong correlation between similar genre movies.

Conclusion
      This project demonstrates the effective use of collaborative            filtering to build a recommendation system using Python.
