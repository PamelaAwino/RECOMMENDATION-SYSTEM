![Uploading image.png…]()


# AMAZON BOOK RECOMMENDATION SYSTEM

## BUSINESS UNDERSTANDING
## OVERVIEW
In the era of exponential data growth, the emergence of more sophisticated systems leveraging big data has become increasingly prevalent. Among these systems, recommendation systems have proven to be valuable information filtering tools, enhancing search results by providing users with more relevant items based on their search queries or browsing history. Major technology companies have embraced recommendation systems across various applications: YouTube utilizes them to determine the next autoplay video, while Spotify employs them to curate personalized "Made for You" daily mixes.
In line with this project's objectives, we aim to harness the power of data analysis to recommend the best books to users. By examining user behaviors, both individual and collective, we can derive insights that enable us to deliver tailored book recommendations that align with their interests and preferences.
The underlying principle of this project is to leverage data-driven techniques to understand user preferences and behaviors. By analyzing user interactions, historical data, and patterns, we can uncover valuable insights that inform our recommendation system. This allows us to present users with a curated list of book suggestions that are highly likely to resonate with their tastes.


### Main Objective
To develop a book recommendation system that leverages data analysis techniques to deliver tailored book recommendations to users, aligning with their interests and preferences.

### Specific Objectives
1. To analyze top book sales: Analyze the sales data of books to gain insights into popular books and trends.
2. To identify peak hours of user activity: Utilize the recommendation system insights to determine the most active periods of the day for users. This information can optimize online ad campaigns to target book enthusiasts during the most engaged periods.
3. To investigate the relationship between book unit prices and quantity demanded: Explore correlations between book prices and the quantity demanded to identify any significant patterns or relationships.
4. To monitor market trends and new book releases: Continuously monitor market trends, new book releases, and emerging genres to keep the recommendation system up to date and relevant.

## DATA UNDERSTANDING
Our dataset is from xxxxxxxxxxxxxxxxxx website

The Book-Crossing dataset comprises three files:

1. Users: Contains anonymized user data, including user IDs (User-ID), demographic information (Location, Age), and NULL values for missing demographic data.
2. Books: Provides information about books, including ISBNs, book titles (Book-Title), authors (Book-Author), year of publication (Year-Of-Publication), publishers (Publisher), and URLs to cover images on Amazon.
3. Ratings: Contains book rating information, including explicit ratings on a scale of 1-10 (Book-Rating) and implicit ratings expressed as 0.

## MODELS IMPLEMENTED
The following models are implemented in this project:

1. Prediction Model: Develop a prediction model within the book recommendation system to accurately forecast the likelihood of a specific user showing interest in a particular book. This model utilizes historical data, user preferences, and interactions.
2. New User Handling: Implement a mechanism to handle new users joining the recommendation system. This mechanism generates initial recommendations based on demographic information, user profiling, and collaborative filtering techniques.
3. Evaluation Metrics: Establish evaluation metrics such as precision, recall, and mean average precision to assess the performance of the recommendation system.
4. Top N Recommendations: Create a function that returns the top N recommendations for a user.
5. Real-time Recommendation Feature: Deploy and implement a real-time recommendation feature that adapts to users' changing preferences. The recommendation model continuously updates by incorporating new user interactions and leveraging real-time data to deliver timely and relevant book suggestions.

6. Collaborative Filtering

7. We used Cosine Similarity to recommend various Books to clients.

8. Memory_Based

9. We used the SVD model to create our model and test our data.

## EVALUATION
The project's success criteria is determined by achieving a Root Mean Squared Error (RMSE) of less than 0.8 for the prediction model. This indicates the accuracy of the model in forecasting user interest in specific books.

## FINDINGS
The findings of the project will include insights into top book sales, peak hours of user activity, the relationship between book prices and quantity demanded, and market trends/new book releases. These findings will inform the recommendation system and contribute to enhancing customer engagement and revenue.

Memory based We used KNN (K-Nearest Neighbours) With Means model has an test RMSE value of xxxxxx and cross validation RMSE value of xxxxxxxx.

Model based

We used the SVD (Singular Value Decomposition) model has a test RMSE score of xxxxxxx and cross validation (CV) RMSE score of xxxxxxx.

## RECOMMENDATIONS
Based on the findings, the following recommendations can be made:

1. Optimize marketing campaigns: Utilize the insights on peak hours of user activity to optimize online ad campaigns and target book enthusiasts during the most engaged periods.
2. Pricing strategies: Analyze the relationship between book prices and quantity demanded to determine if any adjustments in pricing strategies can drive sales.
3. Update recommendation system: Continuously monitor market trends, new book releases, and emerging genres to update and refine the recommendation system, ensuring it remains relevant and provides up-to-date book suggestions to users.

### Author and Acknowledgement:
Special thanks to our Moringa School Data Science Technical Mentors for their guidance throughout the project. We would also like to acknowledge the contributions of the Elites team members:

- Ronald Nyagaka
- Sharon Sonia
- Pamela Awino
- Isaac Muturi
- Leonard Rotich
- Paul Musau
