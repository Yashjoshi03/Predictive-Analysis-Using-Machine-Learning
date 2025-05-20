# Predictive-Analysis-Using-Machine-Learning
COMPANY: CODTECH IT SOLUTIONS

NAME: YASH JOSHI

INTERN ID: CT12DL193

DOMAIN: DATA ANALYTICS

DURATION: 12 WEEKS

MENTOR: NEELA SANTOSH

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
![Image](https://github.com/user-attachments/assets/6b844748-b368-41b3-ab98-462b0a6a1cd0)
![Image](https://github.com/user-attachments/assets/86723df0-7ce2-4fb2-a5e6-f20c2b82e7ed)
![Image](https://github.com/user-attachments/assets/bc81183a-154f-492f-8a26-5c99bc037c20)
![Image](https://github.com/user-attachments/assets/46fc27e5-cc3b-428c-a028-d6df18f26167)
![Image](https://github.com/user-attachments/assets/3e0c7ab3-5351-4ad5-911b-bad407127566)
![Image](https://github.com/user-attachments/assets/eb43136b-b15b-4346-bf67-6ab6c8fdf017)
