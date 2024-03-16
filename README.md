# Bank_Marketing_Effectiveness_Prediction_ML_Classification

Introduction
Traditional marketing strategies in banking have shown limited effectiveness in increasing business. Amid internal competition and financial challenges, European banks sought ways to enhance their financial assets. Direct marketing campaigns, particularly via phone calls, were employed, but the time-intensive nature and low success rates prompted a search for more efficient solutions. The Portuguese Banking Institution has provided data on marketing campaigns conducted over phone calls.

Objective
Analyzing marketing data is a common application of data science and machine learning. This project aims to contribute to the portfolio by achieving two key objectives:

Predicting the outcomes of marketing campaigns for individual customers and identifying factors influencing these outcomes.
Identifying customer segments, particularly those subscribing to term deposits, to tailor marketing campaigns effectively.
Problem Statement
The dataset comprises data from direct marketing campaigns conducted via phone calls by a Portuguese banking institution. The classification task involves predicting whether a client will subscribe to a term deposit.

Attribute Information
Bank Client Data:

Age
Job
Marital status
Education
Default status
Housing loan status
Personal loan status
Related to Last Contact of Current Campaign:

Contact communication type
Last contact month of the year
Last contact day of the week
Last contact duration (in seconds)
Number of contacts performed during this campaign
Number of days passed since the client was last contacted from a previous campaign
Number of contacts performed before this campaign
Outcome of the previous marketing campaign
Output Variable (Desired Target):

Subscription to a term deposit (binary: 'yes' or 'no')
Steps Involved
Loading and exploring data from the CSV file.
Data cleaning to remove incomplete or improperly formatted information.
Exploratory Data Analysis (EDA) to understand data characteristics and relationships.
Importing necessary modules and libraries.
Plotting various graphs to visualize different parameters.
Observing key facts and relationships from graph visualizations.
Data Information
The statistical information contained in the Bank Marketing Effectiveness Prediction Database is based on reports from credible open media sources.

Multicollinearity and VIF
Multicollinearity occurs when independent variables in a regression model are highly correlated. Variable Inflation Factors (VIF) measure the strength of correlation between independent variables.

Outlier Detection and Handling
Outlier detection techniques are used to identify anomalous observations that deviate from the typical distribution of a dataset. Winsorization is a technique used for handling outliers by replacing extreme values with the lower and upper boundaries of the data.

Performance Metrics
Performance metrics such as AUC ROC, Macro-F1 Score, and Confusion Matrix are used to evaluate the effectiveness of machine learning models, particularly in binary classification tasks.

Train and Test Split
Data is split into training and testing sets to estimate the performance of machine learning algorithms.

Handling Imbalanced Dataset
Imbalanced datasets, where one class has significantly more observations than the other, require special attention to prevent bias towards the majority class.

Optimization
Function optimization involves finding the set of inputs that minimize or maximize a target objective function.

Classification Algorithms
Several classification algorithms are explored in this project:

Logistic Regression
Decision Tree
Random Forest
K-nearest Neighbors (KNN)
Naive Bayes
Support Vector Machine (SVM)
LightGBM
Data Visualization Analysis
Data visualization techniques such as correlation heat maps, box plots, line charts, horizontal bar charts, count plots, and distribution plots are used to analyze and interpret data.

Conclusion
Key observations from the analysis include:

Highest subscriptions in the 2nd quarter, particularly in May.
Blue-collar, management, and technician professions showed high interest.
Secondary and tertiary education holders subscribed more.
Cellular communication was more effective.
Longer call durations had higher conversion rates.
KNN and Decision Tree showed promising accuracy for prediction.
References
Python Pandas Documentation: Link
Python Numpy Documentation: Link
Python MatPlotLib Documentation: Link
SciKit Documentation: Link
Towards Data Science: Link
