# Instagram Reach Forecasting
<p align="center">
  <img src="repoIMGs/insta.jpg" alt="instagram" width="200"/>
</p>


## Overview
This repository contains the code and documentation for an Instagram Reach Forecasting project. The goal of this project is to analyze and predict the reach of Instagram posts based on various features such as likes, comments, shares, and more. The insights gained from this analysis can help content creators and marketers understand the factors that contribute to post reach and optimize their social media strategy.

## Project Structure
- **Data Exploration and Analysis:** The project begins with data exploration using Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Plotly Express. The dataset is loaded, and key statistics, correlations, and visualizations are generated to understand the distribution and relationships within the data.

- **Data Preprocessing:** The data is checked for null values, and z-score normalization is applied to handle outliers. The correlation between different attributes is analyzed to identify the strongest relationships.

- **Engagement Rate and User Interaction:** The project calculates the weighted engagement rate to measure the interaction with posts. It also explores the engagement per follower and analyzes the distribution of impressions from various sources, such as the home page, hashtags, and explore page.

- **Correlation Analysis:** The relationships between impressions and various engagement metrics (likes, comments, shares, saves) are examined. Z-score normalization is applied to handle outliers, and the correlation coefficients are calculated. The relationship between profile visits and follower conversion rate is also explored.

- **Machine Learning Models:** Several machine learning models, including Linear Regression, Lasso, Ridge, ElasticNet, RandomForestRegressor, DecisionTreeRegressor, KNeighborsRegressor, and GradientBoostingRegressor, are implemented to predict impressions based on different features. The models are evaluated based on Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) values.

## Results and Insights
1. **Correlation Analysis:**
   - Strong positive correlations are found between impressions and features like likes, shares, and profile visits.
   - Weak correlations are observed between impressions and comments, indicating that comments may not strongly influence impressions.

2. **User Engagement:**
   - Posts with higher impressions tend to have more saves, indicating that users find the content valuable or worth revisiting.

3. **Machine Learning Models:**
   - The Decison Tree Regressor model performs the best in predicting impressions, with an R2 value of 94.69%.

4. **Follower Conversion Rate:**
   - The follower conversion rate, calculated as the percentage of users who follow after visiting the profile, is approximately 41%.

## How to Use


1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ZikriTewelde/instaReachPredictor.git
   cd instagram-reach-forecasting
   
2. **Install Dependencies**
   
   pip install -r requirements.txt

4. **Run Jupyter Notebooks:**

Explore the notebooks in the notebooks directory to understand the data analysis and machine learning processes.

4. **Modify and Experiment:**

Feel free to modify the code and experiment with different features or machine learning models to gain further insights.

## Conclusion

This Instagram Reach Forecasting project provides valuable insights into user engagement, the impact of various features on post reach, and effective strategies for improving content performance. The combination of data analysis and machine learning modeling offers a comprehensive approach to understanding and optimizing social media reach.




