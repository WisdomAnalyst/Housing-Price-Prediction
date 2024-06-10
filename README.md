# House Price Prediction in Lekki, Lagos
This project aims to build a machine learning model to predict the prices of houses in Lekki, Lagos, Nigeria, based on various features such as the number of bedrooms, parking spaces, and house type.

# Dataset
The dataset used in this project is the "Nigeria Houses Data" dataset, which contains information about houses in different towns and states across Nigeria. The dataset includes features such as the number of bedrooms, bathrooms, toilets, parking spaces, and the house type (e.g., Semi-Detached Bungalow, Block of Flats, Detached Duplex).

#  Exploratory Data Analysis
Before building the machine learning model, an exploratory data analysis was performed to gain insights into the dataset and identify potential patterns or relationships between the features and the target variable (house price).

# Key findings from the exploratory data analysis:

Ikoyi has the most expensive houses in Nigeria, closely followed by Maitama District in Abuja.
The number of bedrooms is a significant factor influencing house prices in Lekki. Each additional bedroom contributes approximately ₦20 million to the overall price.
Apartments in a Block of Flats tend to be more expensive than Detached Duplexes, while Semi-Detached Bungalows are generally less expensive.
The number of parking spaces also impacts the house price, with each additional parking space contributing approximately ₦3.5 million to the overall price.
Data Preprocessing
The dataset was preprocessed to prepare it for the machine learning model. The following steps were performed:

Data Cleaning: Removed outliers and handled missing values.
Feature Engineering: Created a new feature called "total_rooms" by summing the number of bedrooms, bathrooms, toilets, and parking spaces.
One-Hot Encoding: Categorical features, such as the house type, were one-hot encoded to convert them into numerical features.
Train-Test Split: The dataset was split into training and testing sets, with 20% of the data reserved for testing.
# Machine Learning Model
A linear regression model with Ridge regularization was used to predict house prices in Lekki. The model was trained on the preprocessed training data and evaluated using the mean absolute error (MAE) metric.

The model achieved a training MAE of ₦X and a testing MAE of ₦Y, indicating a reasonable performance in predicting house prices based on the given features.

# Feature Importance
The importance of each feature in the model was analyzed to understand their relative contributions to the prediction. The top features influencing house prices in Lekki were:

Number of bedrooms
House type (e.g., Semi-Detached Bungalow, Block of Flats, Detached Duplex)
Number of parking spaces
Usage
# To use the trained model for predicting house prices in Lekki, follow these steps:

Install the required Python libraries: numpy, pandas, scikit-learn, and category_encoders.
Load the trained model from the model.pkl file.
Preprocess the input data by one-hot encoding the categorical features.
Use the predict method of the loaded model to obtain the predicted house price.


# Conclusion
This project demonstrates the application of machine learning techniques to predict house prices in Lekki, Lagos, based on various features. The linear regression model with Ridge regularization achieved reasonable performance, and the feature importance analysis provided insights into the key factors influencing house prices in the area.

Future work could involve exploring alternative machine learning algorithms, such as tree-based models or ensemble methods, and incorporating additional relevant features to improve the model's predictive performance.
