# Google Trends Analysis Project 📈🔍

## Introduction 🌐

Explore the intersection of Google Trends data with other time series data to gain insights into various phenomena. This project investigates the relationships between the search volume for specific terms and other metrics such as stock prices, unemployment rates, and more. Key analyses include:

- Understanding how the search volume for "Bitcoin" correlates with the actual price of Bitcoin.
- Analyzing the relationship between search volume for a popular stock like Tesla and its stock price.
- Investigating the variation in searches for "Unemployment Benefits" with changes in the official unemployment rate in the United States.

## What You'll Learn Today 🧠

This project provides hands-on learning experiences in:

- Making time-series data comparable through resampling and conversion to the same periodicity.
- Fine-tuning Matplotlib charts for effective visualization.
- Using grids to visually identify seasonality in time series data.
- Handling missing values in DataFrames.
- Converting string data to datetime objects in Pandas.

## Data Exploration 📊

The project involves exploring and understanding the structure of the provided time series data. Key questions to answer include:

- What are the shapes of the DataFrames?
- How many rows and columns do they have?
- What are the column names?
- What is the largest number in the search data column?
- What is the periodicity of the time series data?

## Data Cleaning 🧹

Identifying and addressing missing or junk values in the DataFrames. This includes finding the number of missing values, locating them, and ultimately removing any rows with missing values.

## Resampling Time Series Data ⏰

Converting daily data to monthly data using the `.resample()` function and addressing the treatment of the data.

## Data Visualisation 📉

### Tesla Line Charts 🚗📈

- Creating line charts to visualize the Tesla stock price against search popularity.
- Styling the charts by adjusting colors, line styles, markers, and chart resolution.
- Exploring the relationship between Tesla-related searches and stock prices.

![Tesla Web Search vs Stock Price](https://github.com/ashay-thamankar/data_analysis/blob/main/Google_trend_analysis/charts/Tesla%20Web%20Search%20vs%20stock%20Price%20time%20series%20line%20chart.png)

### Bitcoin Line Style and Markers 💹🔍

- Plotting Bitcoin search volume against its closing price.
- Experimenting with line styles and markers to enhance the visual appeal of the chart.

![Bitcoin News Search vs Resampled Price](https://github.com/ashay-thamankar/data_analysis/blob/main/Google_trend_analysis/charts/Bitcoin%20News%20Search%20vs%20Resampled%20Price%20time%20series%20line%20chart.png)

### Unemployment: Grids and Rolling Averages ⚖️🔄

- Examining the search volume for "Unemployment Benefits" against the official unemployment rate.
- Adding grids to identify seasonality and patterns.
- Calculating and plotting 6-month rolling averages to observe trends and lead-lag relationships.

![Monthly Search of Unemployment Benefits in the U.S. vs the Unemployment Rate](https://github.com/ashay-thamankar/data_analysis/blob/main/Google_trend_analysis/charts/Monthly%20Search%20of%20Unemployment%20Benefits%20in%20the%20U.S.%20vs%20the%20UnEmplotment%20Rate%20time%20series%20line%20chart.png)

![Rolling Monthly US Unemployment Benefits Web Searches vs UNRATE](https://github.com/ashay-thamankar/data_analysis/blob/main/Google_trend_analysis/charts/Rolling%20Monthly%20US%20Unemployment%20Benefits%20Web%20Searches%20vs%20UNRATE%20time%20series%20line%20chart.png)

### Effect of New Data: 2020 Impact 📉🔄

- Including data from the year 2020 to assess its impact on unemployment and related searches.

![Monthly US Unemployment Benefits Web Search vs UNRATE incl 2020](https://github.com/ashay-thamankar/data_analysis/blob/main/Google_trend_analysis/charts/Monthly%20US%20Unemployment%20Benefits%20Web%20Search%20vs%20UNRATE%20incl%202020%20time%20series%20line%20chart.png)

What we see is not pretty. The US unemployment rate spiked to unprecedented levels during the COVID pandemic, dwarfing the levels seen during the financial crisis. Let's hope the recovery will be swifter this time. 🌐💼

## Additional Analysis and Conclusions 📊🔍

### Tesla vs. Bitcoin Searches

Analyzing the line charts for Tesla and Bitcoin, it's interesting to note that spikes in search volume often precede significant price movements. For Tesla, peaks in web searches coincide with surges in stock prices, suggesting a potential correlation between public interest and market performance.

On the other hand, Bitcoin exhibits a stronger connection between search volume spikes and price increases. This may indicate that public sentiment and interest play a more pronounced role in the volatile cryptocurrency market.

### Unemployment Benefits Search as an Economic Indicator

The analysis of "Unemployment Benefits" searches alongside the official unemployment rate reveals intriguing patterns. Seasonal spikes in searches around December align with historical trends of job market uncertainties during year-end periods.

The introduction of a 6-month rolling average smoothens out fluctuations, emphasizing that spikes in search volume often precede changes in the official unemployment rate. These searches could act as leading indicators, providing insights into shifts in economic conditions before they reflect in official statistics.

### Impact of 2020 on Unemployment Trends

Including data from the tumultuous year 2020 underscores the severity of the COVID-19 pandemic's impact on unemployment. The unprecedented spike in both search volume and the unemployment rate highlights the immediate and profound effect of the crisis on the job market.

## Conclusion 🌐📈

Google Trends data, when combined with other time series data, offers valuable insights into public interest, economic trends, and potential market movements. The visualizations and analyses conducted in this project demonstrate the power of data in uncovering patterns, correlations, and leading indicators.

Understanding the dynamics between online search behavior and real-world phenomena provides a unique perspective for decision-makers in various fields. As we navigate through dynamic economic landscapes and unforeseen events, leveraging such data-driven insights becomes increasingly crucial.

Explore the [complete project](https://github.com/ashay-thamankar/data_analysis/tree/main/Google_trend_analysis).
