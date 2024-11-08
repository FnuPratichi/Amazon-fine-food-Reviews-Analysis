# Amazon Fine Food Reviews Analysis

## 1. Project Overview

The Amazon Fine Food Reviews dataset contains reviews of fine foods sold on Amazon. The dataset includes information such as review scores, product IDs, and user data. This project aims to analyze the reviews and classify them into **positive** and **negative** categories based on the rating.

- **Number of reviews**: 568,454
- **Number of users**: 256,059
- **Number of products**: 74,258
- **Timespan**: Oct 1999 - Oct 2012
- **Number of attributes/columns**: 10

## 2. Objective

The main objective of this project is to classify reviews as **positive** or **negative** based on their rating. 

- **Positive**: Ratings of 4 or 5
- **Negative**: Ratings of 1 or 2
- **Neutral**: Ratings of 3 (ignored in this project)

## 3. Dataset Overview

The dataset contains the following columns:

- **Id**: Unique identifier for each review.
- **ProductId**: Unique identifier for the product.
- **UserId**: Unique identifier for the user.
- **ProfileName**: Name of the user.
- **HelpfulnessNumerator**: Number of users who found the review helpful.
- **HelpfulnessDenominator**: Number of users who indicated whether they found the review helpful.
- **Score**: Rating between 1 and 5.
- **Time**: Timestamp when the review was posted.
- **Summary**: A brief summary of the review.
- **Text**: Detailed text of the review.

## 4. Problem Definition

Given a review, we need to classify it as either **positive** or **negative**:

- **Positive Review**: If the rating is 4 or 5.
- **Negative Review**: If the rating is 1 or 2.
- **Neutral Review**: If the rating is 3 (ignored for this analysis).



