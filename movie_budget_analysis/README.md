# Movie Budget Analysis with Linear Regression

## Introduction
Welcome to the Movie Budget Analysis project! In this project, we explore movie budget and revenue data scraped from [The Numbers](https://www.the-numbers.com/movie/budgets), aiming to answer the question: Do higher film budgets lead to more revenue in the box office?

## Learning Objectives
Today, you'll learn:
- How to use Seaborn, a popular data visualization library.
- How to run and interpret a linear regression with scikit-learn.
- How to plot a regression scatter plot to visualize relationships in the data.
- How to create a bubble chart to represent three dimensions.

## Explore and Clean the Data
Let's start by exploring and cleaning the dataset:
- **Rows and Columns:** The dataset contains 5,391 rows and 6 columns.
- **NaN Values:** No NaN values present.
- **Duplicates:** No duplicate rows.
- **Data Types:** The data types include Rank, USD Production Budget, USD Worldwide Gross, USD Domestic Gross.

### Key Statistics
- Average Production Budget: $31,113,737.58
- Average Worldwide Gross: $88,855,421.96
- Minimum Worldwide and Domestic Revenue: $0.00
- Films Losing Money: 37.2% of films do not recoup their production budget.

### Visualizations
Explore the [Bubble Chart](https://github.com/ashay-thamankar/data_analysis/blob/main/movie_budget_analysis/charts/Movie%20Releases%20over%20Time%20scatter%20plot.png) to see the explosion in movie budgets over the years.

## Decades Analysis
We used floor division to convert the release year into decades:
- Old Films (before 1970): 153 films.
- New Films (1970 onwards): The bulk of films in the dataset.

### Interesting Fact
The most expensive film prior to 1970 was "Cleopatra" with a production budget of $42 million.

## Linear Regression Analysis
We applied a linear regression model to understand the relationship between budget and revenue. The equation of the regression line is:

\[ Revenue = 22,821,538.64 + 3.1 \times Budget \]

Here are the key results:
- Slope Coefficient: $3.1
- Intercept: $22,821,538.64
- R-Squared: 0.029 (indicates a relationship between budget and revenue)

### Predictions
For a $350 million film budget, the estimated revenue is around $600 million.

## Conclusion
The project provides valuable insights into the relationship between movie budgets and revenue, showcasing the industry's growth and the risks associated with film finance.

Feel free to explore the visualizations and dive into the data! 🍿🎬

For a detailed walkthrough and more interactive charts, check out the [Jupyter Notebook](https://github.com/ashay-thamankar/data_analysis/tree/main/movie_budget_analysis).


Let's connect and dive into the fascinating world of movie data!
