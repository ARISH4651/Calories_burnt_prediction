Calories Burnt Prediction 
Overview

This project builds a machine learning model to predict the number of calories burnt during physical activity based on factors such as age, gender, height, weight, duration, heart rate, and body temperature.

The goal is to develop a data-driven approach to estimate calorie burn, which can be useful for:

Fitness tracking applications

Personalized health recommendations

Workout optimization


Features

Data preprocessing and cleaning

Exploratory Data Analysis (EDA) with visualizations

Feature engineering and encoding

Model training (XGBoost)

Model evaluation using MAE, R² Score

Insights on calorie burn factors

 Dataset

The dataset contains physiological and activity features along with target variable Calories.

Features include:

Age

Gender

Height (cm)

Weight (kg)

Duration (minutes)

Heart Rate

Body Temperature

Target variable:

Calories (calories burnt)

Tech Stack

Programming Language: Python 

Libraries & Tools:

pandas, numpy → Data manipulation

matplotlib, seaborn → Visualization

scikit-learn → Machine learning models & evaluation

 Results

The best performing model achieved an R² score of 99%

Weight and Duration were the most significant predictors of calorie burn

The model can be integrated into fitness apps for real-time calorie estimation

Visualizations

Some insights generated during EDA:

Distribution of Age, Height, Weight

Correlation heatmap between features
<img width="666" height="499" alt="image" src="https://github.com/user-attachments/assets/5b9371c7-db01-4f0f-ac1a-d908c87ed356" />
<img width="668" height="493" alt="image" src="https://github.com/user-attachments/assets/5c91d571-e429-47d0-b520-8a49ea9765e2" />

 Future Enhancements

Deploy the model as a Flask/Django web app

Build an API for calorie prediction

Integrate with wearable devices (IoT)

Add deep learning models for more accuracy
