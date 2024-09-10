Copyright (c) 2024 Brad Stafford

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


Website link will take you to 'How to Conduct Stay Interviews: 5 Key Questions' from "SHRM"
     https://www.shrm.org/topics-tools/news/employee-relations/how-to-conduct-stay-interviews-5-key-questions


Project Overview
This project explores employee attrition using a dataset of human resource records. The goal is to understand the factors that influence whether employees leave or stay, using various data analysis techniques and machine learning models.

The project utilizes several key methods such as exploratory data analysis (EDA), regression, classification models, and visualizations to uncover patterns in the data.

Dataset
The dataset used in this project contains employee records, including information such as:

Satisfaction level
Number of projects completed
Monthly working hours
Promotion history
Salary information
Whether the employee left the company
The dataset has been pre-processed to handle missing values and categorical variables.

Key Components
Exploratory Data Analysis (EDA)

Understanding the distribution of features.
Visualizing key relationships such as average monthly hours vs. churn rate.
Visualizations

KDE plots, scatter plots, pie charts, and count plots to illustrate the distribution of employees who left or stayed.
Clustering visualizations using KMeans to understand the relationship between employee satisfaction and evaluation scores.
Modeling

Logistic Regression model for predicting employee churn.
Evaluation of the model based on accuracy.
Future improvements could include hyperparameter tuning and cross-validation.
Clustering

KMeans clustering to identify potential groups within the employees who left.
Future Improvements
Implementation of cross-validation and hyperparameter tuning with Grid Search.
More detailed feature engineering and exploration of additional models.
Libraries Used
numpy
pandas
matplotlib
seaborn
plotly
scikit-learn
How to Run the Notebook
Ensure that you have all the required libraries installed.
Install dependencies via pip:
Copy code
pip install numpy pandas matplotlib seaborn plotly scikit-learn
Download the dataset into the same directory as the notebook.
Open the Jupyter Notebook and run the cells in order.
