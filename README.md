COMPANY: CODTECH IT SOLUTIONS

NAME:   MARAM VIJAY REDDY

INTERN ID:CT06DA368

DOMAIN: DATA ANALYTICS

DURATION: 6WEEKS

MENTOR: VAISHALI


🏠 House Price Prediction using Multiple Linear Regression | Internship Project


📌 Project Overview

This project was developed as part of my internship to demonstrate skills in predictive analytics using machine learning. The goal was to build a regression model that can predict house prices based on several input features that commonly affect real estate value.

The model was trained using a synthetically generated dataset that simulates real-world housing data with fields such as:

   House Age

  Number of Bedrooms and Bathrooms

  Square Footage

  Lot Size

  Number of Floors

  Garage Availability

The project includes full model training, evaluation, and visual insights.


🧰 Tools & Technologies Used



  Google Colab / Jupyter Notebook – Development environment

  Python – Programming language

  Pandas – Data handling and manipulation

  NumPy – Numerical operations

  Scikit-Learn – Model building and evaluation

  Seaborn & Matplotlib – Data visualization


🛠️ Key Tasks
✅ Dataset Generation


  Simulated realistic housing data using NumPy

  Included features like House Age, Bedrooms, Bathrooms, Square Footage, Lot Size, Floors, and Garage

  

✅ Data Exploration & Visualization



  head(), describe() for initial data inspection

  Correlation Heatmap

  Pairplot showing feature relationships

  Price distribution using histograms

   Bar plot showing average price by number of bedrooms

   

✅ Model Building


  Multiple Linear Regression using sklearn

  Train/test split (80/20)

   Fitting the model to training data


✅ Model Evaluation




  R² Score (explained variance)

  Mean Absolute Error (MAE)

  Mean Squared Error (MSE)

  Root Mean Squared Error (RMSE)


  

✅ User Interaction & Prediction




  User prompted to enter housing features

  Model returns predicted price based on user input


  

📊 Visualizations Included



    
   🔥 Correlation heatmap of all features

   📈 Pairplot for multivariate relationships

   📉 Histogram of house price distribution

   🏠 Bar plot of average price vs. number of bedrooms


   

📈 Real-World Applications



This type of regression-based housing price prediction is used in:

  Real Estate Platforms – Price estimation tools for buyers and sellers

  Banking & Mortgages – Automated loan approval based on property valuation

  Urban Planning – Understanding property trends by location

  AI-Powered Investment Tools – Predicting real estate market values



✅ Final Deliverable


A fully-commented, professional Google Colab/Jupyter Notebook containing:

  Synthetic dataset creation

  Feature engineering and EDA

  Model training and evaluation

  5+ visualizationsSample Data:
   HouseAge  Bedrooms  Bathrooms  SquareFeet   LotSize  Floors  Garage  \
0        52         3          3        3823  0.518613       2       1   
1        93         5          2        3642  0.127450       2       1   
2        15         1          3        3267  0.433098       2       0   
3        72         5          3        2835  0.259533       1       1   
4        61         4          2        1721  0.447480       2       0   

           Price  
0  494925.830038  
1  453780.543374  
2  382197.948358  
3  396934.131707  
4  298495.093703

  Live prediction from user input

  Markdown summary with clear insights

  OUTPUT:

  
Sample Data:
   HouseAge  Bedrooms  Bathrooms  SquareFeet   LotSize  Floors  Garage  \
0        52         3          3        3823  0.518613       2       1   
1        93         5          2        3642  0.127450       2       1   
2        15         1          3        3267  0.433098       2       0   
3        72         5          3        2835  0.259533       1       1   
4        61         4          2        1721  0.447480       2       0   

           Price  
0  494925.830038  
1  453780.543374  
2  382197.948358  
3  396934.131707  
4  298495.093703


  
📉 Mean Squared Error: 479398671.750658
✅ R2 Score: 0.9379332940227022

📊 Model Coefficients:
      Feature   Coefficient
0    HouseAge   -209.266762
1    Bedrooms  10421.553815
2   Bathrooms  14208.357839
3  SquareFeet     80.047702
4     LotSize  26848.596263
5      Floors  10217.244144
6      Garage  19622.076604

📊 Model Accuracy Summary:
✅ R² Score: 0.9379 (explained variance)
📉 Mean Absolute Error (MAE): $17,447.10
📉 Mean Squared Error (MSE): $479,398,671.75
📉 Root Mean Squared Error (RMSE): $21,895.17

🏠 Please enter the house details below:
🏡 Enter the age of the house (in years): 4
🛏️ Enter the number of bedrooms: 2
🛁 Enter the number of bathrooms: 3
📐 Enter the square footage of the house: 1200
🌳 Enter the lot size (in acres): 1
🏠 Enter the number of floors (1 or 2): 2
🚗 Does the house have a garage? (1 = Yes, 0 = No): 1

🔮 Predicted House Price: $276,623.04


