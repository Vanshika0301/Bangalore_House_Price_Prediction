# Bangalore House Price Prediction Model

![image](https://github.com/Vanshika0301/Bangalore_House_Price_Prediction/assets/146732449/3fe34fd2-6cd1-480e-9897-884ccbc1a7a5)

## Business Objective
This project aims to predict house prices in Bangalore, India, using machine learning techniques. The model is built using a dataset obtained from Kaggle, which contains information about various factors influencing house prices such as location, size, number of bathrooms, total square feet area, etc.

## Data Source
The dataset used for this project is sourced from Kaggle:
https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data 
It includes information about Bangalore house prices along with details like location, size, total square feet, number of bathrooms, and price.

## Methodology
The project follows the following steps:
- Data Exploration: Understanding the structure and features of the dataset.
- Data Cleaning: Handling missing values and outliers.
- Feature Engineering: Creating new features and transforming existing ones.
- Model Building: Utilizing machine learning algorithms to build a predictive model.
- Model Evaluation: Evaluating the model's performance using appropriate metrics.
- Deployment: Exporting the trained model for future predictions.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Model Selection
The project explores various regression algorithms including Linear Regression, Lasso Regression, and Decision Tree Regression. After evaluating their performance using cross-validation techniques, Linear Regression was chosen as the best performing model.

## Usage
- Clone Repository: Clone this repository to your local machine using git clone https://github.com/your-username/bangalore-house-price-prediction.git
- Install Dependencies: Install the required dependencies using pip install -r requirements.txt
- Run the Model: Execute the model script to train and test the model.
- Predict House Prices: Use the trained model to predict house prices for new data.

## Model Deployment
The trained model is exported as a pickle file (bangalore_home_prices_model.pickle) for easy deployment and usage in other applications. Additionally, the location and column information is exported to a JSON file (columns.json) for reference during prediction.

## Future Improvements
- Incorporating more advanced feature engineering techniques.
- Exploring ensemble learning methods for better model performance.
- Building a web application for user-friendly house price predictions.
