### **Student Performance Prediction**
#### **Overview**
This project aims to predict students' performance index using various factors such as hours studied, previous scores, extracurricular activities, sleep hours, and the number of sample question papers practiced. The model analyzes these features to provide insights into their impact on academic performance.

#### **Dataset**
The dataset used is Student_Performance.csv, containing 10,000 student records with the following columns: <br/>
Hours Studied: The total number of hours spent studying by each student. <br/>
Previous Scores: The scores obtained by students in previous tests. <br/>
Extracurricular Activities: Whether the student participates in extracurricular activities (Yes or No). <br/>
Sleep Hours: The average number of hours of sleep the student had per day. <br/>
Sample Question Papers Practiced: The number of sample question papers the student practiced. <br/>
Target Variable: <br/>
Performance Index: A measure of the overall performance of each student. The performance index represents the student's academic performance and has been rounded to the nearest integer. The index ranges from 10 to 100, with higher values indicating better performance.
#### **Steps**
Data Cleaning: Handle duplicates, missing values, and categorical data <br/>
Data Splitting: Train-test split for model evaluation. <br/>
Model Training: Use Linear Regression to predict the performance index. <br/>
