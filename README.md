# Final-Project-submission
This is made for stamatics project submissions.
# Bulldozer Price Prediction Project

## 📌 Objective
Build a machine learning model to predict the sale price of bulldozers at auction. This helps Fast Iron generate a Blue Book pricing guide for heavy equipment.

## 📂 Dataset
- Source: Provided Train.csv and Test.csv files
- Includes features like machine type, year made, usage hours, auctioneer, and sale date

## 🔍 Data Preprocessing
- Dropped columns with more than 50% missing values
- Filled missing values using median (for numbers) and mode (for text)
- Extracted `saleYear` and `saleMonth` from the `saledate` column
- Encoded categorical variables using Label Encoding

## 🤖 Models Used
1. **Random Forest Regressor**
2. **Linear Regression** (for comparison)

Best model is selected based on RMSLE (Root Mean Squared Logarithmic Error).

## 🧪 Evaluation Metric
- **RMSLE** was used to evaluate model performance
- Final RMSLE on validation data: **0.28**

