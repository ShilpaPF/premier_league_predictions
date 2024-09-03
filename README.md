# Premier League Football Predictions

##Introduction
This project explores the feasibility of using advanced machine learning techniques to predict match outcomes in the English Premier League (EPL). By leveraging a comprehensive dataset from Kaggle, the project implements models such as Random Forest, Gradient Boosting, and Support Vector Machine (SVM) to forecast match results and provide insights into team performance.

## Dataset

### Dataset Source
The dataset used in this project is sourced from Kaggle and includes detailed statistics from recent EPL seasons, such as goals scored, expected goals, possession, and more.
Available on Kaggle: [Premier League Dataset],(https://www.kaggle.com/datasets/tanmaynema/premier-league-match-data-2019-2023)

### Data Privacy
No personal data is used. All data is publicly available match statistics.

### Key Features
The dataset includes 29 features, capturing various aspects of team and player performance.

## Purpose

The primary aim of this project is to develop predictive models to forecast EPL match outcomes with high accuracy. The project also seeks to identify key performance factors, uncover tactical patterns, and optimize strategies using data-driven insights.

## Features

- Data preprocessing and feature engineering.
- Exploratory Data Analysis (EDA) with visualizations.
- Outlier removal using the IQR method.
- Random Forest model for match outcome prediction.
- Feature importance analysis.

## Key Functions
-Data preprocessing and feature engineering.
-Exploratory Data Analysis (EDA) with visualizations.
-Outlier removal using the Interquartile Range (IQR) method.
-Implementation of machine learning models: Random Forest, Gradient Boosting, and SVM.
-Feature importance analysis.
### remove_outliers(df, columns)

Removes outliers using the Interquartile Range (IQR) method.

**Parameters:**
- df (pandas.DataFrame): The input dataframe.
- columns (list): List of column names to check.
**Returns:**
- pandas.DataFrame: Dataframe with outliers removed.

## Output

The script generates visualizations and prints summaries, including:
-Distribution of goals scored.
-Home vs. Away performance comparisons.
-Feature importance for predictions.
-Model accuracy and classification report.

## License

This project is open-source and released under the MIT License.

## Acknowledgements

- Dataset provided by Kaggle.
- Inspired by football analytics communities and previous research in sports analytics.
