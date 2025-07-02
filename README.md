# Airbnb NYC Price Prediction

This project focuses on analyzing and predicting Airbnb listing prices in New York City using the Airbnb NYC dataset from Kaggle. The main goal is to uncover patterns in the dataset through EDA and build a linear regression model to predict prices based on various features.

## 📌 Dataset

- **Source**: [Airbnb NYC 2019 Dataset](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data)
- Contains information like host details, listing price, location, room type, reviews, and availability.

## 🧪 Project Workflow

1. **Exploratory Data Analysis (EDA)**  
   - Analyzed distributions, correlations, and trends across neighborhoods, prices, and availability.
   - Used visualizations (bar plots, scatter plots, heatmaps) to extract insights.

2. **Data Preprocessing**  
   - Handled missing values and removed irrelevant columns.
   - Applied one-hot encoding to categorical variables.
   - Scaled numerical features for better model performance.

3. **Modeling with Linear Regression**  
   - Built and trained a linear regression model using `scikit-learn`.
   - Evaluated model with R² score and RMSE.
   - Visualized actual vs predicted prices.

## 📊 Libraries Used

- `Pandas`  
- `NumPy`  
- `Matplotlib`  
- `Seaborn`  
- `Scikit-learn`

## 🚀 Results

- Identified key features affecting listing prices.
- Linear Regression model provided baseline predictions for price estimation.
- Visualized prediction accuracy and error metrics.

## 💻 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/airbnb-nyc-price-prediction.git
   cd airbnb-nyc-price-prediction
