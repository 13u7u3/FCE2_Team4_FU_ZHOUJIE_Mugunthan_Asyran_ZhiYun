# FCE2_Team4_FU_ZHOUJIE_Mugunthan_Asyran_ZhiYun
Aim: To build predictive models of measuring various measures of a movie' success with advanced machine algorithms

| **SC1015** | **Mini-Project** |
|--------------------------|-------------------------------|
| **Chosen Dataset:**      | TMDB Movie Dataset from Kaggle|
| **Date:**                | April 24, 2024 |
| **Group Number:**        | Group 4 | 
| | |
| | |
| | |
| **TEAM MEMBER**          | **CONTRIBUTIONS** |
| **UMASANKAR MUGUNTHAN**  | Linear Regression, One-hot Encoding, K-Means Clustering, Data-Visualisation & Analysis |
| **NOOR ASYRAN BIN HAMIDON** | Decision Tree Classification, Random Forest, & Analysis |
| **TAN ZHI YUN**           | Data Preparation, Cleaning, & Analysis |


# Project Overview

## Objective:
The aim of this project was to develop a predictive model to gauge various measures of a movie's success using various parameters. We utilized methods such as linear regression, decision trees, random forests, and K-means clustering to analyze the data and extract meaningful insights.

# Data Preparation and Cleaning

We began by cleaning the data, dropping irrelevant columns, and imputing missing values. Outliers were removed to ensure accuracy in calculations.

# Initial Insights

In our initial analysis, we identified relevant pairs of variables. Notably, Revenue and Budget showed a relatively high correlation of 0.713, indicating further exploration. However, correlations involving the month of release were low.

# Linear Regression

We used linear regression to explore relationships between Budget and Profit, and Budget and Viewer Ratings (vote_average).

- **Budget vs Profit:** The analysis revealed a linear relationship with an intercept of -4611948.0147 and a coefficient of 1.9988. The R² value was 0.3116, indicating that approximately 31.16% of profit variability is explained by changes in budget.
- **Budget vs Vote_average:** This pair had a lower R² value of around 0.21, suggesting a weaker correlation.

# One-hot Encoding and Categorization

Categorical variables like movie genres were encoded using one-hot encoding. We categorized movies based on viewer ratings, creating a boolean variable "voted_as_good."

# Decision Trees and Random Forests

- **Decision Trees:** Classification accuracy was relatively low at around 54.1% for predicting average viewer ratings based on budget.
- **Random Forests:** These showed improved accuracy compared to decision trees, with a classification accuracy of approximately 61.2%. Feature importances highlighted Budget as the most influential variable, followed by genres and release month.

# K-means Clustering

- **Utilized an Unsupervised Learning Model** to cluster data points by their proximity to centroid, revealing patterns and correlation within the data.

## Process:
- **Inputs:** One-hot encoded genre columns
- **Optimized parameters:** Determined the Optimal Number of Clusters (K).
- **Model Training:** Implemented the K-means algorithm and trained the model on the preprocessed data.
- **Model Evaluation:** Analyzed clustering results.
- **Interpretation:** Visualized clusters.

## Data-driven Insights:
- The clustering process **enabled easy identification of groupings of movie types** and **provided a clear view of popular mixes of movie genres**.

## Analysis:
- We **identified the most profitable genre combinations**, **guided resource allocation for maximum return**, and **pinpointed flourishing genre combinations**.

## Industry Importance:
- K-means clustering **proved to be key for financial optimization and success**, and **was crucial for strategic decisions**.


# **Conclusion**

**What We Had in Mind?**
Our goal was to determine if we could predict movie success using given variables for our chosen dataset. We aimed to identify any patterns or common characteristics in successful movies.

**How We Achieved It?**
We used a variety of regression and classification techniques, as well as predictive machine learning models to find the best predictors for a movie’s success. We analyzed our findings to look for any patterns that we can use to achieve our goal.

**What We Have Accomplished?**
Despite limitations in our dataset, we were able to use our findings to establish relatively strong correlations and make educated guesses using the variables given. While it is possible to roughly predict a movie’s success using selected variables, it will never be fully accurate due to the unpredictability of the real world.

**What Next?**
We can conclude that it is unlikely for there to be any direct and straightforward relationships in real-life cases. Given a more complete dataset with minimal missing values and more variables, we would be able to develop a more complete and accurate understanding of the elements that contribute to a movie’s success. 

In the future, we can explore gathering additional data, such as information on cast, crew, and marketing campaigns, to enhance our predictive models. This could help us gain deeper insights and improve the accuracy of our predictions.
