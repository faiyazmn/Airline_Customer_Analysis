# AirIndia_Customer_Analysis

## Introduction
The objective of this project is to analyze customer reviews of Indian Airlines to understand customer satisfaction, segment customers, and predict their loyalty.

## Data Summary
Dataset Size: 2,205 reviews.
Features Used: Airline Name, Rating, Review Text, Recommend, Trip Verified, Date.
Source: https://www.kaggle.com/datasets/jagathratchakan/indian-airlines-customer-reviews

## Key Findings
**Customer Satisfaction:**
Out of 2205 customer feedback, 4.03% is the average rating of customers on a 10 point rating scale. And, 3.45% customers said, they will recommend Air India. 	

**Sentiment Analysis:**
Reviews were categorized into Positive, Neutral, and Negative sentiments.
Sentiment scores align with the 'Rating' and 'Recommend' columns. The positive sentiments are 53.96%, negative sentiments are 44.38% and 1.72% are neutral.

**Customer Segmentation:**
Customers were segmented into three clusters based on 'Rating' and 'Sentiment':
Cluster 0: High ratings and positive sentiment.
Cluster 1: Moderate ratings and mixed sentiment.
Cluster 2: Low ratings and negative sentiment.

Predictive Modeling:
The logistic regression model achieved an accuracy of 96.82%
The model can predict whether a customer will recommend the airline based on their review and other features.

## Recommendations
**For Marketing:**
Focus on retaining customers in Cluster 0 with loyalty programs.
Address issues highlighted by customers in Cluster 2 to improve satisfaction.

**For Operations:**
Use insights from negative reviews to identify areas needing improvement.
Enhance customer service and in-flight experience based on feedback.

**Conclusion**
By analyzing customer reviews and leveraging machine learning techniques, we have gained valuable insights into customer satisfaction and loyalty. The clustering and predictive modeling help in understanding customer segments and predicting their likelihood to recommend the airline.

![image](https://github.com/user-attachments/assets/798f4743-7fbb-445b-a8e8-5e3fe77f2aa4)

