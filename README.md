# Predictive-Analysis-Using-Machine-Learning
**COMPANY: CODTECH IT SOLUTIONS

NAME: YASH JOSHI

INTERN ID: CT12DL193

DOMAIN: DATA ANALYTICS

DURATION: 12 WEEKS

MENTOR: NEELA SANTOSH**

# 🌦️ Weather Forecast - Rain Prediction Using Machine Learning

This project builds a machine learning classification model to predict whether it will rain or not based on weather data such as temperature, humidity, wind speed, cloud cover, and pressure.

## 📁 Dataset

- **File:** `Weather Forecast Dataset.csv`
- **Features:**
  - `Temperature`
  - `Humidity`
  - `Wind_Speed`
  - `Cloud_Cover`
  - `Pressure`
- **Target:**
  - `Rain` (Encoded as 0 = No Rain, 1 = Rain)

## 🔍 Exploratory Data Analysis (EDA)

1. **Missing Value Check:**
   - All columns are checked for missing values.

2. **Class Distribution:**
   - A bar chart shows the number of samples for each class (Rain vs No Rain), with counts labeled.

3. **Feature Distributions:**
   - Histograms for each numeric feature to observe their distribution and variance.

## 🧠 Model Building

- **Model Used:** Random Forest Classifier (due to its accuracy, robustness, and ease of interpretation)
- **Steps:**
  - Encode the target column using `LabelEncoder`.
  - Split the data into training and testing sets (80/20).
  - Train the model on the training set.
  - Make predictions on the test set.

## 📈 Model Evaluation

- **Accuracy Score:** Displays the classification accuracy.
- **Confusion Matrix:** A heatmap shows true positives, false positives, etc.
- **Feature Importance:** A horizontal bar chart ranks features based on their contribution to predictions.

## Output:


