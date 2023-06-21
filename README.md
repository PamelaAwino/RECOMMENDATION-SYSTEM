![Alt text](./books-recs-1.png) 

# AMAZON BOOK RECOMMENDATION SYSTEM

## BUSINESS UNDERSTANDING
## OVERVIEW
The objective of this project is to develop a book recommendation system for Amazon that provides personalized suggestions to users based on their individual preferences and reading history. The system aims to enhance customer engagement, improve sales and revenue, increase book discovery, personalize user experience, and gain a competitive advantage in the market.

### Main Objective
The main objective of this project is to develop a book recommendation system that leverages data analysis techniques to deliver tailored book recommendations to users, aligning with their interests and preferences.

### Specific Objectives
1. Analyze top book sales: Analyze the sales data of books to gain insights into popular books and trends.
2. Identify peak hours of user activity: Utilize the recommendation system insights to determine the most active periods of the day for users. This information can optimize online ad campaigns to target book enthusiasts during the most engaged periods.
3. Investigate the relationship between book unit prices and quantity demanded: Explore correlations between book prices and the quantity demanded to identify any significant patterns or relationships.
4. Monitor market trends and new book releases: Continuously monitor market trends, new book releases, and emerging genres to keep the recommendation system up to date and relevant.

## DATA UNDERSTANDING
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

## EVALUATION
The project's success criteria is determined by achieving a Root Mean Squared Error (RMSE) of less than 0.8 for the prediction model. This indicates the accuracy of the model in forecasting user interest in specific books.

## FINDINGS
The findings of the project will include insights into top book sales, peak hours of user activity, the relationship between book prices and quantity demanded, and market trends/new book releases. These findings will inform the recommendation system and contribute to enhancing customer engagement and revenue.

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