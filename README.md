# AIRLINE

# SUMMARY

The project focuses on analyzing airline reviews from 2006 to 2019 to understand customer sentiments and predict whether passengers would recommend the airline to their friends. The dataset includes multiple choice and free text questions, providing valuable insights into passenger experiences.

The primary goal of the project is to help airlines gain a deeper understanding of their customers' opinions and identify areas for improvement. By analyzing the reviews, we can uncover patterns and trends that reveal the factors influencing customer satisfaction and loyalty.

To achieve this, the project involves several key steps. First, we conduct efficient exploratory data analysis (EDA) to gain insights into the dataset's structure, variables, and relationships. This helps us understand the data and identify any data quality issues that need to be addressed.

Next, we preprocess the data to make it ready for training. This includes converting non-numeric values to strings in categorical columns and splitting the data into training and testing sets.

Understanding the target feature, which is whether passengers recommend the airline, is crucial. We analyze its distribution and assess class imbalance to ensure a balanced evaluation of our models.

The project involves modeling the data using different algorithms, such as logistic regression and random forest classification. We evaluate the models' performance while considering class imbalance, as it can impact the accuracy of predictions.

Additionally, we analyze feature importance to identify the key factors driving passenger recommendations. This allows us to provide actionable insights to stakeholders, including airlines, marketing teams, and customer service departments.

Overall, this project offers stakeholders a comprehensive understanding of customer sentiments and preferences. By leveraging the insights gained, airlines can make informed decisions to enhance the passenger experience, improve customer satisfaction, and increase positive recommendations, leading to business growth and success.

# DATASET


Here's a description of the variables in the 'air' dataset:

1. airline: The name or code of the airline.
2. overall: The overall rating given by the customer for their airline experience.
3. author: The author or reviewer of the airline review.
4. review_date: The date when the review was written.
5. customer_review: The text of the customer's review.
6. aircraft: The aircraft used for the flight.
7. traveller_type: The type of traveler (e.g., business, leisure, family).
8. cabin: The type of cabin or class (e.g., economy, business, first class).
9. route: The route or destination of the flight.
10. date_flown: The date when the flight was taken.
11. seat_comfort: The rating for seat comfort.
12. cabin_service: The rating for cabin service.
13. food_bev: The rating for food and beverages.
14. entertainment: The rating for in-flight entertainment.
15. ground_service: The rating for ground services (e.g., check-in, boarding).
16. value_for_money: The rating for value for money.
17. recommended: Whether the customer would recommend the airline to others (1 = Yes, 0 = No).


# CONCLUSION 

The project successfully addressed the objective of predicting passenger recommendations based on airline reviews. By analyzing the dataset and employing machine learning models, valuable insights were obtained for stakeholders, including airlines, marketing teams, and customer service departments.

The project's findings can be used by airlines to understand the factors that drive positive recommendations and improve customer satisfaction. By focusing on specific areas such as seat comfort, cabin service, food and beverages, entertainment, ground service, and value for money, airlines can enhance the overall passenger experience.

Marketing teams can leverage the insights to develop targeted marketing campaigns that emphasize the positive aspects of their services, leveraging the factors that customers value the most. This can lead to increased customer acquisition and retention, as well as positive word-of-mouth recommendations.

Additionally, the project's analysis of the target feature's distribution and class imbalance highlights the need for proactive measures to address potential bias and imbalance in customer recommendations. This awareness can prompt airlines to take corrective actions, such as improving specific areas that receive lower ratings or addressing customer concerns to improve overall customer satisfaction.

Overall, the project's outcome provides actionable insights for stakeholders to make data-driven decisions and improve their services based on customer feedback. By understanding the factors influencing passenger recommendations, airlines can strive to create a positive customer experience, enhance customer loyalty, and gain a competitive edge in the industry.

