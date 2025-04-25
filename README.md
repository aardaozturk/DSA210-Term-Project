# DSA210-Term-Project

# Screen Time and Sleep Patterns Analysis

# Motivation

Our growing reliance on digital devices have created concerns about negatively affected sleep quality. Improving individual health, productivity, and well-being would require us to understand the link between screen usage and sleeping habbits. In order to improve our health and lifestyle, this project will dive into how daily screen usage affects overall sleep quality.



# Main Purposes

- Investigate the patterns between my screen time and sleeping schedule.

- To find if there is a relationship between my screen time and my sleep quality.

- To optimize my daily screen and sleep time to improve my health conditions and lifestyle by using the findings of the project.



# Data Sources

## 1. Screen Time Data (Screen Time App):

Data will be exported from screen time application in Apple.



### Measurements Obtained:



- Hours/minutes of total screen time each day

- Screen time breakdown by app or category (e.g., entertainment, productivity, social media)

- Daily frequency of device unlocks

- Distribution of screen time by day (morning, afternoon, evening, and night)



## 2. Sleep Data (Sleep Tracking App):



Data will be gathered from a sleep tracking application (Da Fit) which is the application of my smart watch.



### Measurements Obtained:

- Total amount of sleep time (hours/minutes)

- Score for sleep quality 

- Sleeping and waking up times

- Number of nighttime awakenings

- Health Information during the sleep period like heart rate





# Hypotheses

In my project, I will consider two different hypotheses, which are stated below.

- H0: There is no relationship between the daily screen time and quality of sleep. Higher screen time does not affect sleep quality.

- Ha: The length and quality of the sleep is being negatively impacted by higher screen time during the day.

*************************************************************************************

- H0’: Screen usage close to sleeping times has no impact on the amount of time it takes to fall asleep. 

- Ha’: Amount of time it takes to fall asleep is increased due to more screen usage close to sleeping times. 




# Data Analysis Plan

Data Preparation:

- Set the data in a specific format that can be effectively used by the algorithm

- Find and handle the outliers and probable missing numbers

- Combine datasets using date and time keys.



### Exploratory Data Analysis (EDA):

In order to achieve the project goals, I am going to implement Exploratory Data Analysis. In the first step, I am going to summarize the screen time and sleep data in order to find patterns and correlations between screen time and sleep quality. Latter, I will split the data to specific timeframes to analyze trends over time. By doing so, the project will be able to explore the hypotheses in a broader way. After implementing all these operations, the findings will be visualized in order to display relations between screen usage and sleep parameters in a comprehensive way. For visualization, I am going to use bar charts, histograms, heatmaps, scatter plots and line graphs to highlight trends, outliers, correlations between these datasets. 



### Statistical Analysis:

For statistical analysis, Pearson’s correlation will help to identify relationships, while regression analysis will assess the predictive power of screen time on sleep quality. Lastly, to further understand how screen time affects sleep outcomes, hypothesis testing will compare groups with high and low screen time.



### Application of Machine Learning:

- Regression algorithms can be used in order to predict sleep quality based on screen time data (Linear Regression, Random Forest Regression, etc.).

- Feature importance analysis can be applied to identify important screen time characteristics which impacts sleep schedule.
