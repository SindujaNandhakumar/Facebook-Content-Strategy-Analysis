# Facebook-Content-Strategy-Analysis

## Introduction:

In today's digital age, social media has become a vital platform for communication and marketing. With the ever-increasing volume of content, it is essential for businesses and influencers to understand what types of posts generate the most engagement. This project is designed to explore the dynamics of social media content effectiveness, particularly in the context of the Thai market.

The primary goal of this project is to analyze the impact of different types of social media content—photos, videos, and text—on user engagement. By leveraging a variety of analytical techniques, including Principal Component Analysis (PCA), clustering, and logistic regression models, we aim to uncover patterns and insights that can guide content strategy.

This study focuses on engagement metrics such as likes, shares, comments, and emotional responses to different content types. By examining these metrics, we hope to identify which forms of content are most effective in capturing user attention and fostering interaction.

The findings from this analysis will provide valuable guidance for marketers and content creators. With data-driven insights, they can optimize their social media strategies to enhance audience engagement, improve content performance, and ultimately achieve better marketing outcomes.

## Overview

**Best Performing Model**: The Logistic Regression model using original features stands out as the best model among those tested. It has the highest Test AUC Score of 0.678, indicating it effectively predicts whether the content is a photo or not. The model balances between sensitivity (detecting photos) and specificity (rejecting non-photos).

**Optimal Features**: Feature selection was performed using Principal Component Analysis (PCA) and clustering to identify the most critical variables that impact social media engagement.

**Target Variable**:The model predicts whether social media content is a photo (binary classification).

## Case - Marketing Consulting Firm in Thailand
**Audience**

Marketing consultants and content strategists.

**Goal**

The project aims to develop a model to predict whether photo content performs better than other content types and to analyze the impact of photo content on social media engagement. This analysis will provide data-driven recommendations for optimizing content strategy

**Target Users**

Businesses and influencers in Thailand using social media for marketing.
**Data**

Includes historical Facebook Live data, engagement metrics (likes, shares, comments, emotional reactions), and content types.

## Analysis Outline

**Part 1**:**Exploratory Data Analysis**  

Checked the data for any null values

Explored the distribution of different content types and engagement metrics..

**Part 2**: **Feature Engineering**

Defined engagement columns and calculated total engagement.

Standardized the dataset and conducted PCA to reduce dimensionality.

**Part 3**: **Model Building**

Built logistic regression models using original features, principal components, and cluster patterns.

**Part 4**: **Model Evaluation**

Evaluated the models based on accuracy, AUC score, and confusion matrix

**Part 5**: **Insight and Recommendation**

**Conclusion**:

The predictive model for social media content type (photo or not) enables the marketing consulting firm to provide data-driven recommendations for optimizing content strategy. The model's performance, with a high AUC score and balanced error metrics, demonstrates its robustness and reliability in real-world applications.


