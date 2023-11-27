# Movie Budget Analysis 🎬💸

## Introduction 🚀

Ever wondered if bigger film budgets translate to blockbuster success? Let's unravel the relationship by diving into the movie budgets and financial performance data scraped from the-numbers.com on May 1st, 2018.

## Definition of Complex Terms 🤔💡

- **Linear Regression:** A statistical wizardry to model the relationship between dependent and independent variables.
- **R-squared:** The magic number revealing how much of the dependent variable's variance is explained by the independent variable(s).
- **Regression Coefficients (θ0, θ1):** The mystical parameters governing the intercept and slope of the regression line.

## Data Exploration and Cleaning 🧹🔍

### Dataset Overview 📊

- **Shape:** (5391, 6)
- **Columns:** Rank, Release_Date, Movie_Title, USD_Production_Budget, USD_Worldwide_Gross, USD_Domestic_Gross
- **Data Types:** int64, object, datetime64[ns]
- **No Missing Values 🚫🕵️**
- **No Duplicate Rows 🔄🚫**

### Data Cleaning 🛁✨

Currency columns converted to numeric, and Release_Date to datetime.

## Descriptive Statistics 📈📉

1. **Average Production Budget:** $31,113,737.58 💰
2. **Average Worldwide Gross Revenue:** $88,855,421.96 🌎💸
3. **Minimums:** Worldwide Gross - $0, Domestic Gross - $0 📉
4. **Bottom 25% Films:** Generally unprofitable, with an average budget of $5 million and worldwide revenue of $3.8 million. 📉💔
5. **Maximums:** Production Budget - $425,000,000, Worldwide Gross Revenue - $2,783,918,982 💰🚀

## Investigating Zero Revenue Films 🔍💰

- **Films Grossed $0 Domestically:** 512 💔
- **Films Grossed $0 Worldwide:** 357 💔
- **High Budget Films with Zero Revenue:** Examples include "Singularity" and "Aquaman." 💸❌

## Unreleased Films 🚫🎥

- **Number of Unreleased Films:** 7
- Excluded these films from further analysis. 🚫🔍

## Films that Lost Money 💸💔

- **Percentage of Films Losing Money:** 37.2% 💔💸

## Data Visualization 📊🎨

### Seaborn Bubble Chart 🌐💭

- A scatter plot visualizing the relationship between production budget and worldwide gross revenue. 🌐💰

### Movie Releases Over Time 📆🎬

- A scatter plot showcasing movie releases over the years, with budget and revenue information.
  ![Movie Releases Over Time Scatter Plot](https://github.com/ashay-thamankar/data_analysis/blob/main/movie_budget_analysis/charts/Movie%20Releases%20over%20Time%20scatter%20plot.png)

## Linear Regression Analysis 📈🔍

### New Films 🆕🎬

- **Slope Coefficient:** 3.12
- **Intercept:** -8,650,768.01
- **R-squared:** 0.56 🚀🔍

### Old Films 🕰️🎞️

- **Slope Coefficient:** 1.65
- **Intercept:** 22,821,538.64
- **R-squared:** 0.03 🕰️📉

## Conclusion 🏁📊

The analysis suggests a positive relationship between movie budgets and worldwide gross revenue. However, the model's predictive power is limited, especially for older films. The industry has seen a significant increase in budgets over the years, with both successes and failures.

## Further Improvements 🛠️🔍

1. Consider additional features for analysis, such as genre, director, or critical reviews. 🎭👩‍🎨
2. Explore non-linear models for better prediction accuracy. 🔄📊
3. Investigate the impact of inflation on budget and revenue figures over time. 📈📉

## Overall Project Link 🔗🌐

[Movie Budget Analysis Project](https://github.com/ashay-thamankar/data_analysis/tree/main/movie_budget_analysis)
