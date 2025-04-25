# 🚗 Car Rental Analytics – Predicting Ride Cancellations

This project aims to help **San Francisco Auto Rental (SAR)** tackle a recurring issue: drivers canceling scheduled rides. Using data analytics and machine learning techniques, we build predictive models that forecast the likelihood of ride cancellations, enabling SAR to take preventive action and improve customer satisfaction.

---

## 📌 Project Objective

- Predict whether a scheduled ride will be **cancelled by the driver**.
- Understand the **key factors** influencing cancellations.
- Segment and analyze bookings using **clustering techniques**.
- Provide actionable insights for **business decision-making**.

---

## 📁 Dataset: `SAR Rental.csv`

A cleaned and structured dataset containing **10,000 records** from 2013 with 19 attributes.  
**Target Variable**: `Car_Cancellation` (0 = No, 1 = Yes)

### 🔑 Key Features:

- `User_ID`, `Vehicle_Model_ID`, `Travel_Type_ID`, `Package_ID`
- `From_City_ID`, `To_City_ID`, `From_Area_ID`, `To_Area_ID`
- `Online_Booking`, `Mobile_Site_Booking`
- `From_Date`, `To_Date`, `Booking_Created`
- `From_Lat`, `From_Long`, `To_Lat`, `To_Long`

---

## 🧰 Tools & Libraries

- Python
- Jupyter Notebook / Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🔄 Project Workflow

### 1. 🧾 Data Preprocessing
- Handled missing values, duplicates, and inconsistent formats
- Converted timestamps and extracted temporal features

### 2. 📊 Exploratory Data Analysis (EDA)
- Visualized trends, patterns, and correlations
- Analyzed cancellation distribution by region, time, and booking method

### 3. 🔍 Predictor Analysis
- Checked feature relevance and multicollinearity
- Applied dimensionality reduction if needed

### 4. 🧱 Data Partitioning
- Split data into **training and testing** sets (e.g., 70/30)

### 5. 🤖 Model Building
- Built and evaluated:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Compared models using:
  - Accuracy
  - Precision, Recall
  - ROC-AUC

### 6. 📉 Clustering (Unsupervised Learning)
- Used K-Means to segment bookings
- Identified behavioral patterns among customers and rides

---

## 📈 Results & Insights

- **High cancellation rates** were linked with specific travel types, vehicle IDs, and areas.
- The **Random Forest** classifier yielded the highest accuracy and balanced performance.
- Clustering revealed user behavior segments, useful for targeted operational improvements.

---

## ✅ Conclusion

The predictive model provides SAR with a **reliable tool** to flag potentially cancellable rides in advance. This enables:
- **Operational efficiency** by allocating backup drivers
- **Improved customer satisfaction**
- **Data-driven strategies** to reduce cancellations

---

## 📂 Repository Structure

