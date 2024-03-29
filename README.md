# Customer-Segmentation-Model-using-Unsupervised-Learning
This project focuses on customer segmentation for a retail company aiming to enhance its marketing strategies through targeted approaches. By leveraging unsupervised learning techniques, specifically clustering algorithms, the project seeks to identify distinct groups of customers based on their spending behavior and demographic attributes.

## Table of Contents
- [Project Objective](#Project-objective)
- [Data Scource](#data-source)
- [Data Processing](#data-processing)
- [Evaluation Metrices](#evaluation-metrices)
- [Key Insights](#key-insights)
- [conclusion and recommendations](#conclusion and recommendations)

## Project Objective
The objective of this project is to build a customer segmentation model for a retail company. By analyzing customer demographics (age, gender) and spending habits (annual income, spending score), the aim is to segment customers based on their spending behavior. The goal is to provide insights that will help the retail company develop targeted marketing strategies.

## Data Source
The dataset used for this analysis was obtained from 10Alytics. The data was collected by the retail company and contains information on 200 customers, including:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score
  
## Data Processing
The data was processed and analyzed using unsupervised learning techniques. Exploratory data analysis (EDA) was performed to understand the characteristics of the dataset. Preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features were carried out to prepare the data for modeling.

## Evaluation Metrices
The effectiveness of the customer segmentation model was evaluated using appropriate metrics such as silhouette score or within-cluster sum of squares (WCSS). These metrics help assess the quality of the clusters generated by the model and guide the selection of the optimal number of clusters.

## key Insights
1. The annual income of the customer ranges from 15 - 137(k) while the spending score of the customers ranges from 1 - 99. The ages of the customers ranges from 18 - 70.
2. There are more female customers than male customers.
3. As the customers age increases, they tend to make less purchases. All age group except the Elder age group have more female customers.
4. The youth age group have the highest spending score while the old adult have the lowest spending score. Suprisingly, the elder age group do not have the lowest spending sore but rather they have the second least spending score.
5. The spending score feature only has a positive correlation (weak) with the annual income.
6. Overall the model divided the customers into 3 segments
- Customers with a low annual income and a high spending score.
- Customers with a low annual income and a low spending score.
- Customers with a high annual income and a high spending score.
- Customers with a high annual income and a low spending score.
- Middle income customers with middle spending score.

## Conclusion and Recommendations
In conclusion, 5 customer segmentation was provided by the model which can inform targeted marketing strategies for the retail company. By tailoring marketing campaigns to the specific needs and preferences of different customer segments, the company can improve customer engagement, loyalty, and ultimately, drive sales and revenue.
