# ML-Models
 A traditional  Machine learning model to find the salary based on the experience.It is implemented in Google Colab, making it easy to run in cloud without any local setup.
# Data set
Source: CSV file hosted on GitHub
The dataset contains two columns:
Years of Experience (input feature)
Salary (target output)
# Setup Instructions (Google Colab)
Open Google Colab.
Create a new notebook.
# Steps to Run
1.Load the Dataset
 Use pandas to read the CSV file from the GitHub URL.
2.Prepare Data
 Separate input (Years of Experience) and output (Salary) columns.
3.Split Data
 Use train_test_split to divide the data into training and testing sets.
4.Train the Model
 Create a LinearRegression model and train it using the training data.
5.Visualize Training Results
 Use matplotlib to plot:
  Red dots for actual training data.
  Yellow line for predicted regression line.
6.Make Predictions
 Predict salaries for test data.
 Accept user input for experience and predict salary.
 Expected Output
A plot showing the relationship between experience and salary.
 Printed test inputs and predicted salaries.
 Predicted salary for user-provided experience.
# Conclusion
This project is a beginner-friendly example of using machine learning for regression tasks. It helps understand how models learn from data and make predictions.
