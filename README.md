# Aman_Java

## Cricket Player Performance Prediction for 2025


---

## Introduction

This Java program predicts future cricket player performance for the year 2025 using linear regression based on historical data (2008 - 2024). The process involves:

- Reading performance data from a CSV file
- Cleaning and processing the data
- Building regression models for each player using Apache Commons Math
- Predicting 2025 performance and evaluating using R-squared values
- Visualizing results with JFreeChart in a GUI

### Dataset Description

The dataset contains detailed cricket player statistics with key columns such as:

- **Player_Name**: Name of the player
- **Matches_Batted**, **Not_Outs**, **Runs_Scored**: Batting performance
- **Highest_Score**, **Batting_Average**, **Balls_Faced**, **Batting_Strike_Rate**
- **Matches_Bowled**, **Balls_Bowled**, **Runs_Conceded**, **Wickets_Taken**: Bowling performance
- **Bowling_Average**, **Economy_Rate**, **Bowling_Strike_Rate**
- **Catches_Taken**, **Stumpings**: Fielding stats

This comprehensive dataset enables thorough analysis and prediction of player performance.

---

## Data Import

The CSV file containing player performance data is read and processed. The data is cleaned and structured into a format suitable for analysis.

![Data Import](images/data_import.png)

---

## Regression Modeling

A linear regression model is built for each player using their historical performance data. This model is used to predict future performance, such as the number of runs each player will score in 2025.

![Regression Modeling](images/regression_modeling.png)

---

## Prediction

The program predicts the runs each player is expected to score in 2025. The prediction accuracy is evaluated using R-squared values.

![Prediction](images/prediction.png)

---

## Model Evaluation

R-squared values are computed for each player’s model to assess its accuracy. The results, including past and predicted performances, are visualized using JFreeChart.

![Model Evaluation](images/model_evaluation.png)

---

## Visualization

### Bar Chart

A bar chart is created to display the previous and predicted performance of each player.

![Bar Chart](images/bar_chart.png)

### Pie Chart

A pie chart illustrates the predicted runs for all players in 2025, providing an overview of the distribution.

![Pie Chart](images/pie_chart.png)

### Histogram

A histogram depicts the distribution of predicted runs for 2025, helping in understanding the spread and frequency of predicted runs across players.

![Histogram](images/histogram.png)

---

## Statistical Analysis

The program conducts statistical analysis on the predicted runs for 2025, including:

- **Mean**: The average of the predicted runs
- **Median**: The middle value of the predicted runs
- **Standard Deviation**: The dispersion or variability of the data around the mean
- **Player with Highest and Lowest Predicted Runs**

![Statistical Analysis](images/statistical_analysis.png)

---

## Libraries

The following libraries are used:

- **Apache Commons Math**: For performing linear regression analysis
- **JFreeChart**: For creating visualizations
- **Java Swing**: For creating the GUI
- **Java AWT**: For layout management
- **Java IO**: For reading data from CSV files
- **Java Util**: For managing collections of data

![Libraries](images/libraries.png)

---

## Conclusion

The program demonstrates the use of linear regression for predicting cricket player performance based on historical data. By leveraging various Java libraries, it provides valuable insights into player performance trends and offers a robust tool for sports analysts, coaches, and enthusiasts.

---

## Code

```java
// https://github.com/AmanRana07/Cricket-Prediction-and-Analysis-Using-Java.git
