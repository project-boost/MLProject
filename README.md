.

🚗 Car Price Prediction Using Machine Learning

A machine learning project that predicts used car prices based on features such as brand, model year, mileage, engine capacity, and more. The project includes data preprocessing, exploratory data analysis (EDA), model building, and performance comparison across multiple algorithms.

📌 Project Overview

This project aims to build a reliable car price prediction model using supervised machine learning techniques.
Three regression models were built and compared:

Linear Regression

Random Forest Regressor

Support Vector Machine (SVM)

Based on evaluation metrics, the Random Forest Regressor delivered the best performance.

🧩 Key Features

End-to-end ML pipeline (cleaning → EDA → modeling → evaluation)

Handling missing values and encoding categorical features

Outlier treatment and correlation analysis

Comparison of ML models using:

R² Score

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

Visualizations for understanding data distribution and model performance

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📊 Model Performance Summary
Model	R² Score	MAE	RMSE
Linear Regression	~0.992	~42615	~57005
Random Forest	~0.989	~50910	~64281
SVM	~0.0002	~538216	~637918
🏁 Conclusion

The Random Forest Regressor shows the best overall performance for car price prediction.
It effectively handles nonlinear relationships and provides consistent predictions.

Linear Regression performs well but lacks precision due to complex feature interactions.
SVM performs poorly without scaling, making it unsuitable for this dataset.
