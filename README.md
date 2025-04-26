# Recommendation_System_in_Python

**COMPANY** : CODTECH IT SOLUTION

**NAME** : ROHIT SONEL

**INTERN ID** : CT4MHBA

**BOMAIN** : MACHINE LEARNING

**BATCH DURATION** : DECEMBER 30TH,2024 TO APRIL 30TH,2025

**MENTOR NAME** : NEELA SANTHOSH KUMAR

#DESCRIPTION OF TASK 4

This project is a movie recommendation system that leverages collaborative filtering techniques to suggest movies to users based on their preferences. The dataset used consists of two primary files: ratings.csv, which contains user ratings for movies, and movies.csv, which includes metadata about the movies such as titles and IDs.
The project begins by importing essential libraries like NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn. The datasets are loaded into Pandas DataFrames for preprocessing and analysis. Key statistics, such as the number of unique users, movies, and ratings, are calculated to understand the dataset's structure. Additionally, user activity frequency and movie rating distributions are analyzed to identify patterns and trends.
To address the issue of sparsity in the dataset, a user-item matrix is created using the scipy.sparse library. This matrix represents the relationship between users and movies, where rows correspond to movies, columns correspond to users, and the values represent ratings. This matrix is essential for implementing collaborative filtering techniques.
The project employs the k-Nearest Neighbors (kNN) algorithm to find similar movies based on user ratings. A function is defined to compute the similarity between movies using cosine similarity. Given a movie ID, the system identifies the most similar movies and returns their IDs, which are then mapped back to movie titles for interpretability.
A recommendation function is also implemented to suggest movies for a specific user. It identifies the highest-rated movie by the user and finds similar movies using the kNN-based similarity function. The recommendations are presented as a list of movie titles, providing personalized suggestions.
The project emphasizes the importance of data preprocessing and feature engineering, such as mapping user and movie IDs to indices and handling sparse data efficiently. It also highlights the use of Bayesian averages to address biases in rating distributions.
Overall, this project demonstrates the practical application of collaborative filtering techniques in building a recommendation system. It provides a foundation for further enhancements, such as incorporating content-based filtering, hybrid approaches, or deep learning models to improve recommendation accuracy. The system can be extended to include additional features like user demographics or movie genres for more personalized recommendations.
