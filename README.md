# Analyzing-Stress-Levels-in-Sleep-Using-Machine-Learning
Machine learning analysis of sleep data to detect stress levels using logistic regression, featuring in-depth data exploration and model evaluation with a dataset found on Kaggle.com.

Project Overview
This repository hosts my data science project aimed at understanding and analyzing stress levels during sleep through machine learning. By utilizing the a dataset found on Kaggle.com (https://www.kaggle.com/datasets/laavanya/human-stress-detection-in-and-through-sleep?select=SaYoPillow.csv) the project explores how different sleep-related factors might be indicative of stress levels.

About the Dataset
The dataset, named "SaYoPillow.csv", includes various parameters related to sleep quality and patterns. These parameters include but are not limited to sleep duration, interruptions, and movement intensity. Data cleaning and preprocessing were significant initial steps to ensure quality and reliability of the analysis.

Methodology
I employed logistic regression for this project, which is an ideal choice for classification problems like stress detection. This project included five target stress levels that the results were categorized into. The project workflow encompasses:

Comprehensive data cleaning and preprocessing.
In-depth exploratory data analysis to uncover initial patterns and insights.
Feature engineering to enhance the predictive power of the model.
Logistic regression model development and validation.
Detailed evaluation of the model using metrics like accuracy, precision, recall, and F1 score.

Key Findings
The project revealed intriguing relationships between various sleep metrics and stress levels. Specific patterns in sleep behavior, when correlated with stress, yielded insightful findings.

Technologies Used
Python for overall data analysis and machine learning.
Libraries like Pandas and NumPy for data manipulation.
Matplotlib and Seaborn for visualizing the data.
Scikit-learn for implementing and evaluating the logistic regression model.

Repository Structure
Detection_of_Stress_Levels_in_Sleep.ipynb: This Jupyter notebook is the heart of the project, containing all the code and analyses from start to finish.
SaYoPillow.csv: The dataset file used for the analysis.
README.md: Provides a comprehensive overview of the project, its structure, and how to replicate the findings.

The dataset was taken from Kaggle.com (https://www.kaggle.com/datasets/laavanya/human-stress-detection-in-and-through-sleep?select=SaYoPillow.csv) and said to cite the following:
1. L. Rachakonda, A. K. Bapatla, S. P. Mohanty, and E. Kougianos, “SaYoPillow: Blockchain-Integrated Privacy-Assured IoMT Framework for Stress Management Considering Sleeping Habits”, IEEE Transactions on Consumer Electronics (TCE), Vol. 67, No. 1, Feb 2021, pp. 20-29.
2. L. Rachakonda, S. P. Mohanty, E. Kougianos, K. Karunakaran, and M. Ganapathiraju, “Smart-Pillow: An IoT based Device for Stress Detection Considering Sleeping Habits”, in Proceedings of the 4th IEEE International Symposium on Smart Electronic Systems (iSES), 2018, pp. 161--166.
