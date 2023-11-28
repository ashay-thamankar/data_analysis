# Dr. Semmelweis' Handwashing Discovery Analysis 🤲🔬📊

## Introduction

Welcome to the Dr. Semmelweis' Handwashing Discovery Analysis project! In this engaging journey, we unravel the compelling story of Dr. Ignaz Semmelweis, a Hungarian physician born in 1818. Dr. Semmelweis played a pivotal role in shaping our understanding of handwashing's significance in medical settings during the 19th century.

## Story Line

Today, you step into the shoes of Dr. Semmelweis, exploring historical medical data to uncover the impact of handwashing on maternal mortality. The analysis covers:

- Preliminary data exploration 📊
- Visualizing births and deaths over time 📈
- Analyzing yearly data split by clinic 👩‍⚕️👨‍⚕️
- Investigating the effect of handwashing 🧴
- Statistical significance testing 🔬

## Objectives

In this analysis, our objectives are to:

- **Explore Data:**
  - Understand the shape, structure, and content of the dataset, covering the years 1841 to 1849, detailing the total number of births and deaths in two maternity clinics.

- **Evaluate Childbirth Risks:**
  - Calculate and visualize the percentage of women who died during childbirth in the 1840s in Vienna, comparing it to modern statistics. 🤰💔

- **Visualize Births and Deaths Over Time:**
  - Create informative Matplotlib charts to visualize the total number of monthly births and deaths, revealing trends and potential anomalies. 📈💔
  - ![Total Number of Births and Deaths Over Time](https://github.com/ashay-thamankar/data_analysis/blob/main/Dr_Semmelweis_Handwashing_Discovery_analysis/charts/Total%20Number%20of%20Births%20and%20Deaths%20time%20series%20over%20years.png)

- **Clinic-wise Analysis:**
  - Analyze the yearly data split by clinic, comparing the births and deaths in two maternity wards at the Vienna General Hospital. 👩‍⚕️👨‍⚕️
  - ![Total Yearly Births by Clinic](https://github.com/ashay-thamankar/data_analysis/blob/main/Dr_Semmelweis_Handwashing_Discovery_analysis/charts/Total%20Yearly%20Births%20by%20Clinic%20line%20chart.png)
  - ![Total Yearly Deaths by Clinic](https://github.com/ashay-thamankar/data_analysis/blob/main/Dr_Semmelweis_Handwashing_Discovery_analysis/charts/Total%20Yearly%20Deaths%20by%20Clinic%20line%20chart.png)

- **Effect of Handwashing:**
  - Investigate the impact of mandatory handwashing on the death rate, both graphically and statistically, showcasing the importance of this practice in reducing mortality. 🧼💧🚿
  - ![Est. Distribution of Monthly Death Rate Before and After Handwashing KDE Plot](https://github.com/ashay-thamankar/data_analysis/blob/main/Dr_Semmelweis_Handwashing_Discovery_analysis/charts/Est.%20Distribution%20of%20Monthly%20Death%20Rate%20Before%20and%20After%20Handwashing%20kde%20plot.png)
  - ![How Have the Stats Changed with Handwashing, Death vs. Handwash](https://github.com/ashay-thamankar/data_analysis/blob/main/Dr_Semmelweis_Handwashing_Discovery_analysis/charts/How%20Have%20the%20Stats%20Changed%20with%20Handwashing%2C%20death%20vs%20handwash.png)
  - ![Percentage of Monthly Deaths Over Time Line Chart](https://github.com/ashay-thamankar/data_analysis/blob/main/Dr_Semmelweis_Handwashing_Discovery_analysis/charts/Percentage%20of%20Monthly%20Deaths%20over%20Time%20line%20chart.png)
  - ![Proportion of Monthly Deaths Histogram Death vs. Washing Hands](https://github.com/ashay-thamankar/data_analysis/blob/main/Dr_Semmelweis_Handwashing_Discovery_analysis/charts/Proportion%20of%20Monthly%20Deaths%20histogram%20death%20vs%20washing%20hands.png)

- **Distribution Analysis:**
  - Use histograms and kernel density estimates to visualize the distribution of monthly death rates before and after handwashing. 📊🔄
  - ![Proportion of Monthly Deaths Histogram Death vs. Washing Hands](https://github.com/ashay-thamankar/data_analysis/blob/main/Dr_Semmelweis_Handwashing_Discovery_analysis/charts/Proportion%20of%20Monthly%20Deaths%20histogram%20death%20vs%20washing%20hands.png)

- **Statistical Significance:**
  - Apply a t-test to determine if the observed differences in death rates are statistically significant. 📉🔍
  - **T-Test Results:**
    - **T-Value:** 5.512
    - **P-Value:** 0.0000002985
    - **Conclusion:** When we calculate the p_value, we see that it is 0.0000002985 or .00002985%, which is far below even 1%. In other words, the difference in means is highly statistically significant. 😊

## Conclusion

Through this analysis, we aim to provide a numerical substantiation of Dr. Semmelweis' groundbreaking work and highlight the critical importance of handwashing in healthcare. The story not only provides historical context but also emphasizes the significance of data-driven decision-making in medical practices. Let's dive into the data and uncover the insights hidden within! 🌐👨‍⚕️👩‍⚕️
