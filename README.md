# Yes-Bank-Stock-Closing-Price-Prediction

![image](https://github.com/Souvik-karmakar/Yes-Bank-Stock-Closing-Price-Prediction/assets/78291973/29fab163-1df2-4fc7-b958-601d571966fe)

## Project Architecture:-

![image](https://github.com/Souvik-karmakar/Yes-Bank-Stock-Closing-Price-Prediction/assets/78291973/f407b6c2-75bc-4fdf-b89a-c961a40ef892)

## Project Summary:-

The goal of this study is to use regression models to forecast stock closing prices. This regression project's summary is explained in the points that follow:-

Data Preprocessing: Following EDA, the dataset underwent cleaning procedures such as the removal of missing values, duplicates, and outliers. Additionally, the data was standardized and features were normalized to ensure consistency.

1. Exploratory Data Analysis (EDA): During this phase, we visualized and analyzed the data to gain insights. This involved data cleaning and preprocessing, including checks for missing values, duplicate records, and outliers. Data visualization techniques were utilized to identify patterns, trends, and relationships.

2. Feature Engineering: New features were engineered from the existing data to enhance model accuracy. This included creating features like Year, Month, and Quarter to capture temporal patterns.

3. Splitting: The dataset was prepared for model implementation by splitting it into training and testing sets. The training set was utilized to train the models, while the testing set was used to evaluate model performance.

4. Model Implementation: Regression models, including Linear Regression, Random Forest Regression, and Decision tree regression were implemented to predict stock prices. Model performance was assessed using metrics such as mean squared error (MSE) and R-squared. Cross-validation techniques were employed to evaluate model performance on unseen data. The Random Forest model with hyperparameter tuning was selected as the final model for production deployment based on a comprehensive evaluation.

5. Model Explainability: Models were analyzed to understand the factors influencing stock price predictions using Permutation Importance Scores explainability tools. Feature importance was assessed, and models were interpreted to elucidate the relationship between features and predicted values.

In summary, this project aimed to predict stock prices using regression models. It encompassed data cleaning, feature engineering, pre-processing, model implementation, and model explainability. The results demonstrated that the implemented Random Forest model with hyperparameter tuning effectively predicted stock prices, achieving the project's objectives.

## Problem Statement:-

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price for the month.

## Conclusion:-

The Yes Bank stock price dataset is devoid of any null/missing values and outliers, ensuring data integrity.

**During data visualization and cleaning:**

1. Skewed features underwent log transformation for normalization.
2. A strong positive linear correlation was observed between the dependent variable and all independent variables.
3. High multicollinearity was detected among the features.
4. A noticeable drop in the stock value post-2017 was identified.
5. A sharp surge in stock price occurred within a 10-month window in 2014. Despite extremely large VIFs indicating equal importance of all variables, no feature engineering was performed.
6. StandardScaler was employed to scale the features uniformly.

**Hypothesis testing revealed:**

1. The mean closing price of Yes Bank stock equals the historical average closing price.
2. Stock closing price exhibits non-stationarity.
3. A significant linear correlation exists between closing prices and high prices.

**Regression models implemented for model selection included:**

1. Linear Regression
2. Hyperparameter-tuned Linear Regression
3. Decision Tree Regressor
4. Hyperparameter-tuned Decision Tree Regressor
5. Random Forest Regressor
6. Hyperparameter-tuned Random Forest Regressor
   
**Key conclusions from model implementation:**

1. The Hyperparameter-tuned RandomForest regressor was chosen as the final model for its superior performance.
2. Permutation Importance Scores indicated that the "Low" feature holds the highest importance in predicting the target variable, followed by the "High" feature. Conversely, "Open," "Year," "Month," and "Quarter" 3. features displayed relatively low importance, with "Open" being the least significant among them.


