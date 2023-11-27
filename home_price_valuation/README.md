# Boston Housing Price Prediction and Home Price Valuation Data Analysis

## Home Price Valuation Data Analysis

Welcome to the Home Price Valuation Data Analysis project! 🏡💰 In this project, we analyze various factors influencing home prices to gain valuable insights.

### Project Overview
For a detailed overview of the project and its components, please visit the [Home Price Valuation Data Analysis](https://github.com/ashay-thamankar/data_analysis/tree/main/home_price_valuation) page.

### Project Data 📊

### Charts

#### Employment vs Price Joint Plot
![Employment vs Price Joint Plot](https://github.com/ashay-thamankar/data_analysis/blob/main/home_price_valuation/charts/emp%20vs%20poll%20joint.jpg)

#### Home Price Displot
![Home Price Displot](https://github.com/ashay-thamankar/data_analysis/blob/main/home_price_valuation/charts/house%20price%20displot.png)

#### Price and Residual Analysis
![Price and Residual Analysis](https://github.com/ashay-thamankar/data_analysis/blob/main/home_price_valuation/charts/price%20%20residual%20analysis.png)

#### Residual vs Actual Plot with Regression Line
![Residual vs Actual Plot with Regression Line](https://github.com/ashay-thamankar/data_analysis/blob/main/home_price_valuation/charts/residual%20vs%20actual%20plot%20with%20regression.png)

#### Number of Rooms vs Home Price Joint Plot
![Number of Rooms vs Home Price Joint Plot](https://github.com/ashay-thamankar/data_analysis/blob/main/home_price_valuation/charts/room%20vs%20%20home%20price%20joint%20plot.png)

#### Number of Rooms Displot
![Number of Rooms Displot](https://github.com/ashay-thamankar/data_analysis/blob/main/home_price_valuation/charts/rooms%20displot.png)

#### Skew Plot
![Skew Plot](https://github.com/ashay-thamankar/data_analysis/blob/main/home_price_valuation/charts/skew%20plot.png)


## Boston Housing Price Prediction

### Overview 🏡

Welcome to our Boston Housing Price Prediction project! In this analysis, we aim to predict residential property prices in Boston, Massachusetts, during the 1970s. We consider various features such as the number of rooms, distance to employment centers, neighborhood characteristics, and more.

#### Project Data 📊

- **Dataset Details:**
  - Number of Instances: 506
  - Number of Attributes: 13 numeric/categorical predictive features
  - Target Variable: Median value of owner-occupied homes in $1000's (PRICE)

- **Features:**
  1. CRIM: Per capita crime rate by town
  2. ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.
  3. INDUS: Proportion of non-retail business acres per town
  4. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
  5. NOX: Nitric oxides concentration (parts per 10 million)
  6. RM: Average number of rooms per dwelling
  7. AGE: Proportion of owner-occupied units built prior to 1940
  8. DIS: Weighted distances to five Boston employment centers
  9. RAD: Index of accessibility to radial highways
  10. TAX: Full-value property-tax rate per $10,000
  11. PTRATIO: Pupil-teacher ratio by town
  12. B: \(1000(Bk - 0.63)^2\) where Bk is the proportion of blacks by town
  13. LSTAT: Percentage of the lower status of the population

#### Project Execution 🚀

##### 1. Data Analysis and Exploration 📈

We initiated our analysis by exploring the dataset. Key steps include:

- Examining the shape, column names, and information about the data.
- Conducting preliminary data exploration to understand key statistics and characteristics.
- Checking for missing values and duplicates.

##### 2. Visualizing Key Features 📊

We used various visualizations to gain insights into important features:

- **House Prices Distribution:**
  - Highlighting a spike in the number of homes at the $50,000 mark.
  - ![House Prices Distribution](https://github.com/ashay-thamankar/data_analysis/blob/main/home_price_valuation/charts/emp%20vs%20poll%20joint.jpg)

- **Distance to Employment Centers:**
  - Visualizing the distribution of distances to Boston employment centers.
  - ![Distance to Employment Centers](https://github.com/ashay-thamankar/data_analysis/blob/main/home_price_valuation/charts/house%20price%20displot.png)

- **Number of Rooms:**
  - Exploring the distribution of the average number of rooms per dwelling.
  - ![Number of Rooms](https://github.com/ashay-thamankar/data_analysis/blob/main/home_price_valuation/charts/price%20%20residual%20analysis.png)

- **Accessibility to Highways:**
  - Investigating the index of accessibility to radial highways.
  - ![Accessibility to Highways](https://github.com/ashay-thamankar/data_analysis/blob/main/home_price_valuation/charts/residual%20vs%20actual%20plot%20with%20regression.png)

- **Next to Charles River:**
  - Analyzing the distribution of homes located next to the Charles River.
  - ![Next to Charles River](https://github.com/ashay-thamankar/data_analysis/blob/main/home_price_valuation/charts/room%20vs%20%20home%20price%20joint%20plot.png)

##### 3. Regression Modeling 🧠

We employed Multivariable Regression to predict property prices. The initial model achieved an r-squared of 0.75 on the training data. Key steps included:

- Evaluating coefficients to understand the impact of each feature on property prices.
- Analyzing residuals to check for systematic biases in the model.
- Transforming data using logarithmic prices to improve model performance.

##### 4. Model Evaluation 📉

We assessed the model's performance using both the original and log-transformed prices. The log-transformed model demonstrated an improved r-squared of 0.79 on the training data.

##### 5. Out-of-Sample Performance 🔄

On the test data, the log-transformed model outperformed the original model, achieving an r-squared of 0.74 compared to 0.67.

#### Conclusion 🎉

Our analysis demonstrates the effectiveness of predicting Boston housing prices using regression models. The log-transformed model, in particular, shows promising results. Further refinement and exploration could enhance the model's accuracy and generalization.

#### Further Improvements 🚧

1. **Feature Engineering:**
   - Explore additional feature combinations or transformations for improved model performance.
   - Consider interaction terms between certain features.

2. **Advanced Modeling:**
   - Experiment with more advanced regression models.
   - Explore ensemble methods for better predictions.

3. **Data Quality:**
   - Continuously monitor and handle outliers or anomalies in the dataset.
   - Explore the impact of normalizing or scaling features.

4. **Interactive Visualization:**
   - Develop interactive visualizations to enhance user engagement.
   - Utilize tools like Plotly for dynamic exploration.

#### Project Repository 📂

For detailed code implementation and additional insights, refer to our [GitHub repository](https://github.com/ashay-thamankar/data_analysis/tree/main/home_price_valuation).

Feel free to explore, contribute, and share your feedback! 🌐

