# British Airways Virtual Internship: Flight Booking Prediction ✈️  

This project is part of the **British Airways Virtual Internship on Forage**, focusing on predicting whether a customer will complete a flight booking. The analysis involves **data preprocessing, exploratory data analysis (EDA), machine learning modeling, and evaluation** to uncover key insights and improve predictive accuracy.  

## 📌 Project Overview  
### Goals  
- Analyze booking-related factors to predict flight booking completion.  
- Develop a machine learning model to classify customers based on their likelihood to complete a booking.  
- Identify key features influencing booking behavior to optimize business strategies.  

## 📊 Dataset & Features  
The dataset includes various booking attributes, such as:  
- **Purchase Lead**: Days between booking and flight departure.  
- **Length of Stay**: Duration of stay at the destination.  
- **Flight Hour**: Time of flight departure.  
- **Additional Preferences**: Extra baggage requests, preferred cabin class, etc.  

## 🔍 Project Workflow  
### 1️⃣ Data Preprocessing  
- **Handled outliers** (e.g., capped `purchase_lead` and `length_of_stay` at the 95th percentile).  
- **Encoded categorical variables** using one-hot encoding.  
- **Split dataset** into training and testing sets for model evaluation.  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Analyzed feature distributions and correlations.  
- Investigated relationships between `purchase_lead`, `length_of_stay`, and `flight_hour` with booking completion.  
- **Developed visualizations** (heatmaps, histograms, and correlation plots) using Matplotlib and Seaborn.  

### 3️⃣ Machine Learning Model  
- **Implemented a Random Forest Classifier** to predict booking completion.  
- **Achieved 85.53% accuracy** on the test set.  
- **Performed cross-validation**, yielding an average accuracy of **73.08%**, to assess model robustness.  
- **Evaluated model performance** using classification reports and confusion matrices.  

### 4️⃣ Key Insights  
- **Feature Importance**:  
  - `purchase_lead` and `wants_extra_baggage` were key predictors of booking completion.  
  - Length of stay and flight hour also influenced customer booking behavior.  
- **Model Performance**:  
  - The Random Forest model performed well, but additional tuning and feature selection could enhance accuracy further.  

## 🛠 Technologies Used  
- **Programming Language**: Python  
- **Libraries & Tools**:  
  - Data Processing: Pandas, NumPy  
  - Visualization: Matplotlib, Seaborn  
  - Machine Learning: Scikit-learn  
  - Model Evaluation: Accuracy, Precision, Recall, F1-Score  
