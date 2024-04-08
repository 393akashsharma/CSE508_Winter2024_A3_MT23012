# CSE508 Information Retrieval Winter 2024 Assignment-3 Report

## Introduction

The advent of the e-commerce era has revolutionized shopping experiences, offering consumers an abundance of choices. In this landscape, product recommendation systems play a crucial role in guiding users through the vast array of options available. Personalized suggestions tailored to individual preferences have become essential for enhancing user experience, increasing engagement, and ultimately driving customer satisfaction.

## Objective

The primary objective of this project is to develop a robust product recommendation system leveraging collaborative filtering techniques. Collaborative filtering involves analyzing user interactions and preferences to generate personalized recommendations. By utilizing Amazon review data as our primary data source, we aim to provide tailored suggestions that cater to individual interests, thereby enhancing user engagement and satisfaction.

## Data Acquisition and Preprocessing

Our dataset comprises two main components: a 5-core dataset and metadata. The metadata, extracted from a gzip file containing information on electronics products, underwent preprocessing to filter relevant information and prepare it for analysis. Descriptive statistics were computed to gain insights into customer reviews, including the calculation of average rating scores and counts of good and bad ratings. Text preprocessing techniques were applied extensively to clean and standardize text data, ensuring consistency and accuracy in subsequent analyses.

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) served as a vital preliminary step in understanding the characteristics and structure of our dataset. By analyzing descriptive statistics, we gained insights into various aspects of the data, including the distribution of ratings and top-reviewed brands within the 'mouse' category. EDA helped us identify key patterns and trends, laying the foundation for the development of our recommendation system.

## Machine Learning Models

Several machine learning models were evaluated for sentiment classification based on customer reviews. Models such as Logistic Regression, Linear SVC, SGD Classifier, Passive Aggressive Classifier, and Naive Bayes were trained and assessed using performance metrics such as precision, recall, and F1-score. This evaluation provided valuable insights into the effectiveness of each model in accurately classifying sentiment.

## Collaborative Filtering

Collaborative filtering techniques were employed to create user-item rating matrices and implement user-user and item-item recommender systems. By analyzing similarities between users and items using cosine similarity, personalized recommendations were generated based on user preferences. Mean Absolute Error (MAE) was calculated to quantify the performance of the recommender systems, providing a measure of prediction accuracy.

## Results

The collaborative filtering approach yielded promising results, offering personalized recommendations based on user-item interactions. Insights into user and item preferences were obtained, laying the groundwork for further refinement and optimization of the recommendation system.

## Conclusion

In conclusion, the development of a product recommendation system using collaborative filtering techniques proved successful. By leveraging Amazon review data and employing advanced machine learning algorithms, we were able to generate personalized suggestions tailored to individual user preferences. The system holds potential for enhancing user engagement, improving shopping experiences, and ultimately driving customer satisfaction in the e-commerce landscape.

Clone this project by :-https://github.com/393akashsharma/CSE508_Winter2024_A3_MT23012

AKASH KUMAR
MT23012
