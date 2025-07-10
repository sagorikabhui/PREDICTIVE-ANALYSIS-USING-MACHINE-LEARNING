# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

COMPANY: CODTECH IT SOLUTIONS

NAME: SAGORIKA BHUI

INTERN ID: CITS0D79

DOMAIN: Data Analytics

DURATION: 4 WEEKS

MENTOR: Neela Santhosh

DESCRIPTION:

Project Overview:

This project focuses on analyzing a dataset related to student performance across three major subjects: Math, Reading, and Writing. The primary objective is to gain insights from the data using exploratory data analysis (EDA) and to implement a Linear Regression model that predicts student performance based on several features like gender, parental level of education, lunch type, and test preparation course.

By using data visualization and machine learning techniques, we aim to identify patterns in academic performance and understand how different socio-economic and personal factors may influence students' scores. This analysis can help educators, parents, and academic institutions make data-driven decisions to improve student outcomes.


Dataset Information:

The dataset used in this project is StudentsPerformance.csv. It contains 1000 rows and 8 columns with the following features:

gender

race/ethnicity

parental level of education

lunch

test preparation course

math score

reading score

writing score



Step-by-Step Process:

Step 1: Importing Libraries and Loading the Data

Basic Python libraries like pandas, numpy, matplotlib, and seaborn were imported. The dataset was read into a DataFrame using pandas, and the first few rows were displayed for a quick look.

Step 2: Data Inspection

We used .info(), .isnull().sum(), and .describe() to explore the dataset. It was found that there were no missing values, and data types were appropriate for analysis.

Step 3: Data Preprocessing

Categorical variables like gender, race/ethnicity, parental education, lunch type, and test preparation course were encoded into numeric format using label encoding. This was essential for feeding the data into the machine learning model.

An additional column, average score, was created by averaging the scores in math, reading, and writing. This metric gave a more holistic view of a student’s performance.

Step 4: Model Building

We used Linear Regression, a basic yet effective machine learning model, to predict the average score of a student based on the input features.

The steps involved:

Splitting the dataset into features (X) and target (Y)

Further splitting into training and test sets using train_test_split

Creating and training the model with LinearRegression()

Predicting on the test data

Step 5: Model Evaluation

The model was evaluated using R² Score, which came out to be 1.0, indicating a perfect fit on this dataset. This means the model was able to explain all the variability in the target variable with the given features.


Visual Insights:

Several visualizations were used to better understand the data:

Bar plots of average scores grouped by gender

Comparisons of average scores based on parental level of education

Box plots for analyzing score distributions

Correlation heatmaps for numeric relationships


These visualizations helped uncover meaningful patterns, such as:

Male students slightly outperforming in math, while females scored higher in reading and writing

Students whose parents had higher education levels performed better

Students with standard lunch and completed test prep performed significantly better


Conclusion:

This task demonstrates how simple EDA and machine learning can be used to extract valuable insights from educational data. It highlights the impact of social and demographic factors on academic performance and builds a predictive model that can help in student performance forecasting.

The project is a great example of using data science for educational improvement and lays the groundwork for further enhancements like classification models or advanced regressors.
