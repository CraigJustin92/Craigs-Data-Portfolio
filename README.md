A collection of my data projects showcasing skills in data processing, visualization, and analysis. Explore how I turn data into actionable insights.


# [Project 1: Netflix Content Prediction](https://github.com/CraigJustin92/Netflix_Content_Prediction)

**Objective:**  
Unlock the secrets behind Netflix’s content acquisition strategy by predicting which movies are likely to be fast-added (within the first year of release) based on various features.

**Approach:**
- **Data Exploration:** Delved into the dataset to uncover trends and patterns in movie features such as genre, release year, and duration.
- **Data Cleaning:** Ensured data integrity by filtering out invalid coordinates and handling missing values.
- **Feature Engineering:** Calculated distances between pickup and dropoff locations and added a `season` feature to capture seasonal trends.
- **Predictive Modeling:** Developed and evaluated models using machine learning algorithms to identify key predictors of fast-added movies.
- **Hypothesis Testing:** Applied chi-squared tests to explore relationships between categorical variables and movie success.

**Insights & Findings:**
- Discovered strong predictors of fast-added movies that can drive strategic content decisions.
- Visualized relationships between features to highlight key trends and patterns in content acquisition.

**Recommendations:**
- Explore additional features like viewer ratings and historical content performance to refine predictions.
- Experiment with advanced modeling techniques to enhance prediction accuracy.
- Continuously update the model with new data to adapt to changing content trends.

Dive into the details to see how these insights can transform Netflix's content strategy and drive its next big hits!

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


# [Project 3: Insights and Strategies for Improved Returns Management](https://public.tableau.com/shared/HSJ99SQZZ?:display_count=n&:origin=viz_share_link)

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
