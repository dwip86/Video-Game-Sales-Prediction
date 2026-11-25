📌 Project Overview

Video Game Sales Prediction is a Machine Learning project that predicts the global sales of video games based on different features such as Platform, Genre, Release Year, and Publisher.

The project uses the vgsales.csv dataset and applies different regression algorithms to estimate video game sales across the global market.

🎯 Project Objectives

Analyze video game sales data.

Understand sales trends across different platforms and genres.

Perform data cleaning and Exploratory Data Analysis (EDA).

Build Machine Learning regression models.

Compare model performance.

Predict global video game sales.

📂 Dataset Information

Dataset Name: vgsales.csv

The dataset contains information about video games, including:

Rank

Name

Platform

Year

Genre

Publisher

NA_Sales

EU_Sales

JP_Sales

Other_Sales

Global_Sales

Target Variable: Global_Sales

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

Google Colab

🤖 Machine Learning Algorithms

Linear Regression

Decision Tree Regressor

Random Forest Regressor

⚙️ Project Workflow

Import required libraries.

Upload and load the dataset.

Explore the dataset.

Check missing and duplicate values.

Clean and preprocess the data.

Perform Exploratory Data Analysis (EDA).

Analyze genre-wise, year-wise, and platform-wise sales.

Select input features and target variable.

Encode categorical features.

Handle missing values.

Split the dataset into training and testing sets.

Train three regression models.

Evaluate model performance.

Perform 5-Fold Cross-Validation.

Apply hyperparameter tuning.

Generate predictions.

Compare model performance.

Select and save the best model.

📊 Model Evaluation

The models are evaluated using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Confusion Matrix

🔍 Input Features

Platform

Genre

Year

Publisher

🎯 Target Variable

Global_Sales (in millions)

📈 Sales Classification

For additional evaluation, predicted sales are converted into two categories:

Low Sales: Less than 1 million

High Sales: 1 million or more

📁 Project Structure

Video-Game-Sales-Prediction/
│
├── vgsales.csv
├── Video_Game_Sales_Prediction.ipynb
│
├── project_results/
│   ├── best_video_game_sales_model.pkl
│   ├── final_model_comparison.csv
│   ├── final_cross_validation_results.csv
│   ├── hyperparameter_tuning_results.csv
│   └── confusion matrix files
│
└── README.md

🚀 How to Run the Project

Download or clone the project repository.

Open Google Colab or Jupyter Notebook.

Upload the vgsales.csv dataset.

Open Video_Game_Sales_Prediction.ipynb.

Run all cells step by step.

View the graphs, model evaluation, and prediction results.

🏁 Conclusion

This project demonstrates how Machine Learning techniques can be used to predict global video game sales. It compares Linear Regression, Decision Tree, and Random Forest models using different evaluation metrics and cross-validation techniques.

The best-performing model is selected and saved for future predictions.

👨‍💻 Author
Dwip Shil

Machine Learning Project – Video Game Sales Prediction
