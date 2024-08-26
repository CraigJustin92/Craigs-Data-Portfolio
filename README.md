A collection of my data projects showcasing skills in data processing, visualization, and analysis. Explore how I turn data into actionable insights.


# [Project 1: Netflix Content Prediction](https://github.com/CraigJustin92/Netflix_Content_Prediction)

**Objective:**  
Develop predictive models to identify movies likely to be fast-added (within the first year) to Netflix, aiming to enhance content acquisition strategies and maximize viewer engagement.

**Approach:**
- **Data Exploration:** Analyzed features such as genre, release year, duration, etc., to identify characteristics of fast-added movies.
- **Data Cleaning:** Addressed missing values, corrected inconsistencies, and removed duplicates.
- **Feature Engineering:** Created new features and selected relevant ones for modeling.
- **Model Development:** Applied decision trees, random forest, and XGBoost to predict fast-added movies.

**Summary of Model Results:**
- **Decision Trees:** Achieved a precision of 70.7%, recall of 75.3%, F1-score of 72.9%, and accuracy of 69%. Removing the `movie_duration` feature improved recall to 82.1% and F1-score to 73.6%.
- **Random Forest:** Delivered an AUC of 77.1%, precision of 72.3%, recall of 78.1%, F1-score of 75.1%, and accuracy of 72.3%. This model outperformed the decision tree model.
- **Extreme Gradient Boosting (XGBoost):** Reached an AUC of 77.0%, precision of 72.1%, recall of 76.9%, F1-score of 74.4%, and accuracy of 71.2%. While XGBoost performed better than the decision tree, the random forest model surpassed it in all metrics.

**Insights & Findings:**
- **Mature-Themed Content Demand:** The strong preference for TV-MA or R-rated content suggests a need for more mature-themed programming to boost viewer engagement and retention.
- **Model Performance:** The random forest model provided the best overall performance, indicating it as the preferred choice for predicting fast-added content.
- **Feature Impact:** The removal of certain features (e.g., `movie_duration`) can significantly impact model performance metrics.

**Recommendations:**
- **Data Collection:** Enhance data collection on viewer engagement, social media trends, regional preferences, production quality, awards, and marketing impact.
- **Feature Engineering:** Develop interaction features between genres and countries, and consider seasonal trends for more accurate predictions.
- **Metric Tailoring:** Adjust model parameters based on Netflix’s strategic priorities for improved alignment with content acquisition goals.

**Next Steps:**
- **Feature Engineering:** Further explore interaction features and seasonal analysis to refine predictions.
- **Metric Tailoring:** Adjust model parameters based on Netflix’s strategic priorities for improved alignment with content acquisition goals.

![Random Forest Classifier: Top 10 Feature Importances](https://github.com/CraigJustin92/Craigs-Data-Portfolio/blob/main/images/netflix%20feature%20importance.png?raw=true)
___

# [Project 2: Uber Fare Prediction Model](https://github.com/CraigJustin92/Uber-Fare-Prediction-Model)

**Objective:**  
Develop a predictive model to estimate Uber fare amounts based on features such as distance traveled, number of passengers, and time of day.

**Approach:**
- **Data Preparation:** Validated coordinates, selected key features, and log-transformed fare amounts to address skewness.
- **Feature Engineering:** Calculated the distance between pickup and dropoff locations and added a `season` feature to capture seasonal trends.
- **Model Building:** Applied `StandardScaler` to normalize features, built and evaluated an OLS model, and assessed performance using metrics like R-squared, MSE, and MAE.
- **Visualization:** Created scatter plots and histograms to analyze relationships and distribution.

**Insights & Findings:**
- **Strong Correlation:** Distance is highly correlated with fare amounts (Pearson coefficient of 0.74), indicating that longer trips generally lead to higher fares.
- **Model Performance:** 
  - **R-squared:** 0.634, showing that the model explains 63.4% of the variance in fare amounts.
  - **Mean Squared Error (MSE):** 0.080, indicating the average prediction error is relatively low.
  - **Mean Absolute Error (MAE):** 0.207, suggesting the model’s predictions are, on average, within about 21 cents of the actual fare.

**Recommendations:**
- Include additional features such as traffic conditions or weather to improve accuracy.
- Experiment with advanced models and perform hyperparameter tuning for better performance.
- Investigate and manage outliers that could affect predictions.
- Continuously refine the model based on performance metrics to enhance accuracy and reliability.

Explore how these findings can lead to more accurate fare predictions and improve the overall Uber ride pricing strategy!

![Distance vs Fare Amount](https://github.com/CraigJustin92/Craigs-Data-Portfolio/blob/main/images/uber%20distance%20vs%20fare.png?raw=true)

![Heatmap of Average Fare Amount by Day and Season](https://github.com/CraigJustin92/Craigs-Data-Portfolio/blob/main/images/uber%20fare%20by%20day%20and%20season.png?raw=true)
___

# [Project 3: Insights and Strategies for Improved Returns Management](https://public.tableau.com/views/UncoveringtheImpactonSalesandProfitability/AreYourDiscountsHurtingYourProfitsUncoveringtheImpactonSalesandProfitability?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

**Objective:**  
Analyze returns data to identify trends and improve returns management strategies for an eCommerce company, focusing on return rates, the number of returns, and sales data.

**Approach:**
- **Data Integration:** Consolidated returns, sales, and product category data into a comprehensive dataset.
- **Data Cleaning:** Addressed inconsistencies and missing values to ensure data quality.
- **Visualization:** Created interactive Tableau dashboards to visualize return rates, return numbers, and trends over time.
- **Trend Analysis:** Analyzed patterns in return rates and the number of returns across different categories and distribution centers (DCs).

**Insights & Findings:**
- **Decreasing Return Rate:** Despite an increase in the number of returns, the return rate has been declining, indicating better product quality and improved customer satisfaction.
- **High Return Categories:** Certain categories, such as jeans and clothing sets in Europe, have higher return rates, suggesting a need for targeted quality control and packaging improvements.
- **Logistics Concerns:** Some DCs exhibit higher return numbers, pointing to potential logistical issues that require attention.

**Recommendations:**
- **Targeted Quality Control:** Improve the quality of products in high-return categories, such as Blazers and Jackets for Australian customers.
- **Enhanced Packaging:** Upgrade packaging standards for products with high return rates to minimize damage during shipping.
- **Customer Feedback Integration:** Use customer feedback to identify common return reasons and address these issues proactively.

Explore the interactive Tableau dashboards to understand how these insights can enhance returns management and improve overall operational efficiency.
[link to dataset](https://www.kaggle.com/datasets/mustafakeser4/looker-ecommerce-bigquery-dataset)

![Return Rate Overtime](https://github.com/CraigJustin92/Craigs-Data-Portfolio/blob/main/images/returns%20management%201.png?raw=true)
![3 Categories with Highest Return Rates](https://github.com/CraigJustin92/Craigs-Data-Portfolio/blob/main/images/returns%20management%202.png?raw=true)

