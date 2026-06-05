# RECOMMENDATION-SYSTEM

*COMPANY* : CODTECH IT SOLUTIONS 

*NAME* : PATEL KRISHKUMAR VASANTBHAI

*INTERN ID* : CTIS9788

*DOMAIN* : MACHINE LEARNING 

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOS


This project focuses on building a Movie Recommendation System using User-Based Collaborative Filtering on the MovieLens dataset. Recommendation systems play a crucial role in modern digital platforms by helping users discover relevant content based on their interests and past interactions. The primary objective of this project is to recommend movies to users by identifying other users with similar rating patterns and leveraging their preferences to generate personalized suggestions.

The project begins with loading and exploring the MovieLens ratings dataset. Basic exploratory data analysis is performed to understand the number of ratings, users, and movies available in the dataset. This step provides insights into the data distribution and helps identify the overall structure of the dataset. A rating distribution graph is also created to visualize how users rate movies, enabling a better understanding of user behavior and rating trends.

After data exploration, a User-Movie Matrix is constructed using a pivot table. In this matrix, rows represent users, columns represent movies, and the values correspond to movie ratings. Missing ratings are replaced with zeros to facilitate similarity calculations. This matrix serves as the foundation for the recommendation process, as it captures the interaction between users and movies in a structured format.

To identify users with similar preferences, cosine similarity is applied to the User-Movie Matrix. Cosine similarity measures the similarity between users based on their rating patterns. The resulting similarity scores are stored in a User Similarity Matrix, which quantifies how closely related users are to one another. A heatmap visualization is generated to display these similarity scores, making it easier to observe relationships and clusters among users.

The recommendation engine is then implemented using User-Based Collaborative Filtering. For a selected user, the system identifies the most similar users and analyzes the movies they have highly rated. Based on these ratings and similarity scores, recommendation scores are calculated for unseen movies. The movies with the highest scores are returned as the top recommendations. These recommendations are displayed and further visualized using a bar chart that highlights the top recommended movies and their corresponding recommendation scores.

To evaluate the performance of the recommendation system, the Root Mean Square Error (RMSE) metric is calculated. RMSE provides a measure of prediction accuracy by comparing actual ratings with predicted values. Although a simple baseline approach is used in this project, the evaluation demonstrates the importance of measuring recommendation quality and provides a foundation for future improvements.

Overall, this project successfully demonstrates the implementation of a User-Based Collaborative Filtering Recommendation System using machine learning techniques. Through data preprocessing, similarity computation, recommendation generation, visualization, and evaluation, the project showcases how personalized movie recommendations can be created from user rating data. The developed system serves as a practical introduction to recommendation systems and provides a strong foundation for implementing more advanced approaches such as Item-Based Collaborative Filtering, Matrix Factorization, and Hybrid Recommendation Systems in future work.


# OUTPUT :
<img width="800" height="500" alt="Image" src="https://github.com/user-attachments/assets/c3972bf2-c2d2-4145-ac11-fdc850fd600d" />
<img width="1000" height="500" alt="Image" src="https://github.com/user-attachments/assets/0a445c79-bfea-4241-9cd6-4e2974411073" />
<img width="1000" height="800" alt="Image" src="https://github.com/user-attachments/assets/d642cecb-98a9-4e97-97dc-a61c1e5f1a3b" />
