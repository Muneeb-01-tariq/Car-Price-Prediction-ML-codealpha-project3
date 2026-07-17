# Car-Price-Prediction-ML-codealpha-project3
# 🚗 Car Price Prediction using Machine Learning

A Machine Learning regression project that predicts the selling price of used cars based on various features such as present price, car age, kilometers driven, fuel type, transmission, and ownership history. This project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, exploratory data analysis (EDA), model training, and performance evaluation using Python and Scikit-learn.

---

## 📌 Project Overview

The objective of this project is to build a regression model capable of predicting the selling price of a used car using historical car data. Two machine learning algorithms were trained and compared to identify the best-performing model.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing.
- Explore the dataset using visualization techniques.
- Create new features to improve model performance.
- Train regression models for car price prediction.
- Evaluate and compare model performance.
- Understand real-world applications of machine learning in the automobile industry.

---

## 📂 Dataset

The dataset contains information about used cars, including:

- Car Name
- Year
- Selling Price (Target Variable)
- Present Price
- Driven Kilometers
- Fuel Type
- Selling Type
- Transmission
- Number of Previous Owners

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning
5. Feature Engineering
6. Encode Categorical Variables
7. Exploratory Data Analysis (EDA)
8. Train-Test Split
9. Train Linear Regression Model
10. Train Random Forest Regressor
11. Model Evaluation
12. Performance Comparison
13. Visualization of Results
14. Conclusion

---

## 📈 Exploratory Data Analysis

The following visualizations were created:

- Correlation Heatmap
- Selling Price Distribution
- Fuel Type Distribution
- Transmission Type Distribution
- Present Price vs Selling Price
- Car Age vs Selling Price
- Actual vs Predicted Price Comparison

---

## 🤖 Machine Learning Models

### Linear Regression

- Simple and interpretable regression model.
- Used as the baseline model.

### Random Forest Regressor

- Ensemble learning algorithm.
- Provides better prediction accuracy by combining multiple decision trees.

---

## 📏 Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score (Coefficient of Determination)

---

## 📁 Project Structure

```
Car-Price-Prediction
│
├── Car_Price_Prediction.ipynb
├── car data.csv
├── README.md

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/yourusername/Car-Price-Prediction.git
```

2. Navigate to the project folder

```bash
cd Car-Price-Prediction
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open the Jupyter Notebook

```bash
jupyter notebook
```

5. Run all cells in **Car_Price_Prediction.ipynb**

---

## 📌 Results

- Successfully preprocessed the dataset.
- Created a new feature (Car Age) for improved prediction.
- Trained both Linear Regression and Random Forest Regression models.
- Compared model performance using multiple regression metrics.
- Built a machine learning model capable of predicting used car selling prices with good accuracy.

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV.
- Try advanced boosting algorithms such as XGBoost or CatBoost.
- Deploy the model using Flask or Streamlit.
- Build an interactive web application for price prediction.

---

## 👨‍💻 Author

**Muhammad Muneeb Tariq**

Data Science Student

---

## ⭐ If you found this project helpful, don't forget to star this repository!
