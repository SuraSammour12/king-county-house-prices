# 🏡📈 House Sales Analysis & Price Prediction – King County, USA 

This project focuses on analyzing and predicting residential housing prices in King County, Washington, including Seattle. The primary goal is to explore how features like square footage, number of bedrooms, and location influence housing prices, and to build regression models for accurate price prediction.



##  Project Objectives

- Load and inspect the King County house sales dataset.
- Clean the dataset and handle missing values or incorrect data.
- Perform Exploratory Data Analysis (EDA) to uncover key price-influencing factors.
- Develop regression models including:
  - Simple Linear Regression
  - Multiple Linear Regression
  - Ridge Regression with hyperparameter tuning
- Evaluate model performance and refine for better accuracy.



##  Dataset Description

The dataset includes house sales in King County, WA, from May 2014 to May 2015.

| Feature            | Description                                        | 
|--------------------|----------------------------------------------------|
| id                 | Unique house ID                                    |
| date               | Date house was sold                                | 
| price              | Price the house was sold for (Target Variable)     | 
| bedrooms           | Number of bedrooms                                 | 
| bathrooms          | Number of bathrooms                                |
| sqft_living        | Square footage of the home                         |
| sqft_lot           | Square footage of the lot                          |
| floors             | Number of floors                                   | 
| waterfront         | Waterfront view (1: yes, 0: no)                    | 
| view               | Quality of the view (0–4)                          | 
| condition          | Overall condition (1–5)                            | 
| grade              | Construction and design grade (1–13)               | 
| sqft_above         | Square footage above ground                        |
| sqft_basement      | Square footage of basement                         | 
| yr_built           | Year built                                         |
| yr_renovated       | Year renovated (0 if never)                        |
| zipcode            | Zip code                                           | 
| lat                | Latitude                                           | 
| long               | Longitude                                          | 
| sqft_living15      | Living room size of 15 nearest neighbors           | 
| sqft_lot15         | Lot size of 15 nearest neighbors                   | 



##  Technologies Used

- **Python**
- **Pandas & NumPy** → Data Manipulation
- **Matplotlib & Seaborn** → Data Visualization
- **Scikit-learn** → Regression Models (Linear & Ridge)
- **Jupyter Notebook** → Interactive Analysis



##  Project Structure

├── data/

│ └── kc_house_data.csv

├── notebooks/

│ └── KingCounty_Housing_Analysis.ipynb

├── README.md

└── requirements.txt


##  Expected Outcomes

- Identify which features have the highest influence on housing prices.
- Build and evaluate regression models for price prediction.
- Improve model accuracy through Ridge regularization and hyperparameter tuning.
- Provide insights that assist investment decisions for residential real estate in King County.

##  Example Price Predictions

Using the trained model, we can predict house prices based on key features:

| House | sqft\_living | bedrooms | bathrooms | floors | waterfront | Predicted Price |
| ----- | ------------ | -------- | --------- | ------ | ---------- | --------------- |
| 1     | 1340         | 3        | 1.0       | 1      | No         | \$311,907.69    |
| 2     | 3000         | 4        | 2.5       | 2      | Yes        | \$1,890,630.86  |
| 3     | 1000         | 2        | 1.0       | 1      | No         | \$240,174.39    |



##  License

This project is for educational purposes only and uses the dataset under public domain (CC0 1.0 Universal).


##  Useful Links

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Original Dataset Source (Kaggle)](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)


##  Summary

This project provides a practical end-to-end application of data science principles to real estate data. It walks through data cleaning, visualization, model development, and evaluation to predict housing prices accurately and guide real estate investment decisions.

