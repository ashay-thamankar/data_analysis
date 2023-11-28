# Nobel Prize Analysis Project 🏆📊

## Introduction 🚀

Welcome to the Nobel Prize Analysis project, where we delve into the historical data of Nobel laureates to uncover patterns, trends, and insights. Established by Alfred Nobel, the Nobel Prize is awarded to individuals and organizations that have made outstanding contributions to humanity in various fields, including chemistry, literature, physics, physiology or medicine, economics, and peace.

## Data Overview 📈

The dataset used in this analysis contains information about Nobel laureates, including their birth dates, motivations for winning, prize shares, and more. The analysis spans from the inception of the Nobel Prize in 1901 up to the latest available data.

## Data Exploration & Cleaning 🧹

### Preliminary Exploration 🕵️‍♂️

- **Shape of df_data:** The dataset contains a certain number of rows and columns, providing an overview of the data's size.
- **Column Names and Data Types:** Examining the column names and their corresponding data types helps in understanding the information available in the dataset.
- **First Nobel Prize Year:** Determining the year in which the first Nobel Prize was awarded sets the historical context.

### Data Cleaning 🧼

- **Handling Duplicates:** Identifying and addressing any duplicate entries in the dataset.
- **Date Conversion:** Converting date columns, such as birth_date and year, into appropriate datetime objects.
- **Percentage Share Calculation:** Adding a column, share_pct, to represent the laureates' share as a percentage.

## Exploration and Visualization 🔍📈

The core of the analysis involves exploring and visualizing the data to derive meaningful insights:

- **Percentage of Male vs. Female Winners:** Utilizing a Plotly Donut Chart to visualize the distribution of male and female Nobel laureates. ![Percentage of Male vs. Female Winners](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/Percentage%20of%20Male%20vs.%20Female%20Winners_pie_chart.png)

- **Exploration by Category:** Examining the distribution of Nobel Prizes across different categories, identifying repeated winners, and analyzing the trends over time. ![Number of Prizes Awarded per Category](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/Number%20of%20Prizes%20Awarded%20per%20Category%20bar%20chart.png)

- **Geographical Analysis:** Utilizing Choropleth maps and bar charts to depict the distribution of Nobel Prizes among countries and cities. ![World Map with Prize Count](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/world%20map%20with%20prize%20count.png)

- **Age Analysis:** Investigating the age distribution of laureates at the time of receiving the prize, identifying the oldest and youngest winners, and exploring age trends over time and across categories. ![Distribution of Age on Receipt of Prize](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/Distribution%20of%20Age%20on%20Receipt%20of%20Prize%20histplot.png)

- **Number of Nobel Prizes Awarded per Year:** Using a scatter plot with a trend line to visualize the annual distribution of Nobel Prizes. ![Number of Nobel Prizes Awarded per Year](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/Number%20of%20Nobel%20Prizes%20Awarded%20per%20Year%20scatter%20and%20line%20chart.png)

- **Number of Prizes Awarded per Country (Yearwise):** Analyzing the distribution of prizes among countries over the years using a bar chart. ![Number of Prizes Awarded per Country (Yearwise)](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/Number%20of%20prizes%20per%20country%20yearwise.png)

- **Top 20 Countries by Number of Prizes:** Identifying the top 20 countries with the highest number of Nobel Prize winners using a bar chart. ![Top 20 Countries by Number of Prizes](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/Top%2020%20Countries%20by%20Number%20of%20Prizes%20bar%20chart.png)

- **Top 20 Research Institutions by Number of Prizes:** Highlighting the top 20 research institutions with the highest number of Nobel Prize winners using a bar chart. ![Top 20 Research Institutions by Number of Prizes](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/Top%2020%20Research%20Institutions%20by%20Number%20of%20Prizes%20bar%20chart.png)

- **Where Were the Nobel Laureates Born?:** Exploring the birthplaces of Nobel laureates using a bar chart. ![Where Were the Nobel Laureates Born?](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/Where%20were%20the%20Nobel%20Laureates%20Born%20bar%20chart.png)

- **Which Cities Do the Most Research?:** Identifying the cities with the highest research contributions using a bar chart. ![Which Cities Do the Most Research?](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/Which%20Cities%20Do%20the%20Most%20Research%20bar%20chart.png)

- **Winning Age Over Time:** Analyzing the winning age of Nobel laureates over time using a scatter plot with a regression line. ![Winning Age Over Time](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/winning%20age%20over%20time%20scatter%20with%20regression%20line.png)

- **Winning Age vs. Category:** Exploring the relationship between winning age and prize category using a box plot. ![Winning Age vs. Category](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/winning%20age%20vs%20category%20box%20plot.png)

- **Winning Age Over Years:** Investigating how the winning age of Nobel laureates has changed over the years using a scatter plot with a regression line. ![Winning Age Over Years](https://github.com/ashay-thamankar/data_analysis/blob/main/Noble_Prize_Analysis/charts/winning%20age%20over%20years%20scatter%20with%20regression%20line.png)

## Challenges 🤔

The challenges provided in the project guide the exploration and analysis, prompting questions and considerations that enhance the depth of the investigation.

## Conclusion 🎉

The Nobel Prize Analysis project offers a comprehensive exploration of historical data, uncovering patterns that reflect the evolution of the Nobel Prize over time. Through visualizations and analytical insights, this project provides a deep understanding of the achievements and demographics of Nobel laureates. Enjoy the journey of discovery! 🚀
