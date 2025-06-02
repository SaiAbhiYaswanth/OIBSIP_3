Car Price Prediction 
with Machine Learning

Abstract: 

Predicting the resale price of used cars is a significant challenge in the automotive industry 
due to the wide range of factors influencing a vehicle’s value. This project aims to develop a 
machine learning-based model to accurately estimate the selling price of pre-owned cars 
using various features such as the car's age, present price, kilometres driven, fuel type, 
ownership history, transmission, and selling type. 
A cleaned and pre-processed dataset is used to train a regression model, with special attention 
to feature engineering and categorical variable encoding. Multiple regression algorithms were 
tested, and Random Forest Regressor was found to provide high accuracy and robustness. The 
model’s performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean 
Squared Error (MSE), and R-squared (R²). 
In addition to numerical evaluation, visual tools like feature importance plots and actual vs. 
predicted value scatter plots are used to analyse the model’s effectiveness. The results 
demonstrate that machine learning models can significantly improve price prediction 
accuracy, providing a valuable tool for car buyers, sellers, and dealerships. The model can be 
further enhanced for deployment in real-world applications such as price comparison 
websites and dealership inventory systems. 

Introduction: 

The used car market has seen rapid growth in recent years, with increasing demand for 
reliable, affordable pre-owned vehicles. One of the most challenging aspects of this market is 
accurately determining the selling price of a used car, as it depends on various factors such as 
the brand, model, year of manufacture, fuel type, mileage, ownership history, and more. 
Traditional methods of car valuation often rely on manual assessments and subjective 
judgments, which can lead to inconsistent and inaccurate pricing. 
With the advancement of data science and machine learning, it is now possible to develop 
models that can learn from historical data and make accurate price predictions based on 
specific features. This project focuses on building a machine learning model that can predict 
the resale price of used cars using a dataset containing various car attributes. The aim is to 
help both buyers and sellers make informed decisions and bring transparency to the pricing 
process. 
The dataset used in this project includes features such as the present price of the car, 
kilometres driven, type of fuel, transmission type, number of owners, and more. After 
preprocessing and feature engineering, different regression algorithms are applied to train the 
model. The performance of the model is evaluated using common regression metrics and 
visual tools to ensure reliability and accuracy. 
This project not only demonstrates the practical application of machine learning in the 
automobile sector but also serves as a stepping stone for building intelligent pricing systems 
in e-commerce platforms, car dealerships, and resale websites.

Objective: 

The primary objective of this project is to develop a machine learning model that can 
accurately predict the selling price of used cars based on various features of the vehicle. The 
specific goals are: 
1. To analyse and understand the key factors that influence the resale value of a car, such 
as age, mileage, fuel type, transmission, and ownership. 
2. To preprocess and transform the dataset by handling missing values, encoding 
categorical variables, and engineering new features for improved model performance. 
3. To apply and compare different regression algorithms (e.g., Linear Regression, Random 
Forest, Boost) to find the most suitable model for predicting car prices. 
4. To evaluate the performance of the trained models using appropriate regression 
metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean 
Squared Error (RMSE), and R² Score. 
5. To visualize model predictions and feature importance to gain insights into the model’s 
decision-making process and overall accuracy. 
6. To build a reliable and efficient system that can assist users (buyers, sellers, or 
dealerships) in estimating the fair price of a used vehicle.

Methodology: 

The methodology followed in this project involves several key stages, each crucial to building 
an accurate and reliable car price prediction model using machine learning techniques. The 
steps are as follows: 
1. Data Collection 
The dataset used in this project contains information on various features of used cars, 
including: 
 Car Name 
 Year of Manufacture 
 Present Price 
 Selling Price (Target variable) 
 Kilometres Driven 
 Fuel Type 
 Transmission Type 
 Selling Type 
 Number of Owners 
The dataset is assumed to be collected from a trusted source, possibly an automobile resale 
portal or public dataset repository. 
2. Data Preprocessing 
 Feature Selection and Cleaning: Unnecessary columns like Car Name are dropped due 
to high cardinality and low predictive power. 
 Feature Engineering: A new column Carriage is created by subtracting the year of 
manufacture from the current year to better represent the car’s age. 
 Encoding Categorical Variables: Categorical features like Fuel Type, Transmission, and 
Selling Type are converted into numerical values using one-hot encoding. 
 Handling Outliers and Data Types: The data is examined for outliers and inconsistencies 
to ensure clean input for the model. 
3. Exploratory Data Analysis (EDA) 
 Visualizations such as histograms, box plots, and scatter plots are used to understand 
feature distributions and relationships. 
 Correlation Matrix is used to analyse the strength of relationships between numerical 
features and the target variable (Selling price). 
4. Splitting the Data 
 The dataset is split into training and testing sets using an 80:20 ratio to evaluate model 
performance on unseen data.
5. Model Building 
Multiple regression models are trained and evaluated: 
 Linear Regression: For a baseline model. 
 Random Forest Regressor: For handling non-linearity and complex interactions. 
 Boost Regressor (optional): For improved accuracy and efficiency. 
6. Model Evaluation 
 The models are evaluated using performance metrics: 
o Mean Absolute Error (MAE) 
o Mean Squared Error (MSE) 
o Root Mean Squared Error (RMSE) 
o R² Score 
 Visualization of Actual vs. Predicted Prices helps assess the model's prediction 
capability visually. 
7. Model Interpretation and Feature Importance 
 The contribution of each feature to the final prediction is analysed using feature 
importance scores from the trained Random Forest model. 
8. Model Deployment (Optional) 
 The trained model is saved using jilbab or pickle for future use or integration into a 
web or desktop application for user-friendly prediction.

Conclusion: 

This project successfully demonstrates how machine learning can be effectively applied to 
predict the resale price of used cars based on various features. By performing thorough data 
preprocessing, feature engineering, and model training using algorithms such as Random 
Forest Regressor, we achieved accurate and reliable price predictions. 
The model was evaluated using key regression metrics such as Mean Absolute Error (MAE), 
Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score, along with 
visualizations like actual vs. predicted value plots. These evaluations confirmed that the model 
performs well and can generalize to unseen data. 
This car price prediction system can be a valuable tool for individuals, car dealers, and online 
platforms looking to estimate the fair value of a used vehicle quickly and efficiently. With 
further improvements—such as integrating a larger and more diverse dataset, adding more 
relevant features (like insurance status or accident history), and deploying the model via a 
web interface—the system can be scaled for real-world commercial use. 
In summary, this project highlights the practical application of machine learning in the 
automotive domain and lays the foundation for more advanced pricing tools in the future.
