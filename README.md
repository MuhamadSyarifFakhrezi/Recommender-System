# Recommender-System

## Business Understanding

Amazon is one of the largest e-commerce platforms in the world that provides a wide range of products, including fashion. With millions of users and products, providing relevant recommendations can improve users' shopping experience, increase sales, and drive customer loyalty.

## Project Objective

The aim of this project is to develop a recommendation system that can help users find fashion products they like based on their previous shopping behaviour. The recommendation system will use implicit feedback data, such as purchase history and product ratings, to suggest products that may be of interest to users.

**Main Objectives**
Users: Increase user satisfaction by providing relevant and interesting product recommendations.
Merchants: Increase sales of fashion products by introducing products to users who may be interested.
Platform: Increase user engagement and time spent on the platform by providing a personalised shopping experience.

## Analysis Approaches

This project utilises the [Amazon](https://amazon-reviews-2023.github.io/) dataset for fashion product categories which includes information on purchase history and product ratings by users (Downloadable [here](https://datarepo.eng.ucsd.edu/mcauley_group/data/amazon_2023/raw/review_categories/Amazon_Fashion.jsonl.gz)). The recommendation model is built using the Alternating Least Squares (ALS) algorithm by utilising implicit feedback data. Exploratoty Data Analysis process was also conducted to find out the distribution, description, and insight of the data, Laplace Smoothing approach was used to help prevent bias towards products with few high-ranking reviews in the top products ranking process by adding a constant to each category to avoid zero probability.

## Business Benefits

Increased Sales: Relevant recommendations can encourage users to buy more products.
User Satisfaction: A personalised shopping experience can increase user satisfaction and loyalty.
Marketing Efficiency: By knowing user preferences, marketing campaigns can be more targeted and effective.
