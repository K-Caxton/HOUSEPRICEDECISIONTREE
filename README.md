#  House Price Prediction Using Decision Tree Regression

A Machine Learning project that predicts house prices using a **Decision Tree Regressor** implemented in Python with Scikit-learn. The project demonstrates the complete machine learning workflow, from data preprocessing to model evaluation and visualization.

---

##  Project Overview

The objective of this project is to predict house prices based on several property characteristics, including:

- Area (Square Feet)
- Number of Rooms
- Property Type
- Location
- Street Type
- Furnishing Status
- House Age Category
- Swimming Pool Availability

The trained model learns patterns from historical housing data and estimates the market price of new properties.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Graphviz
 

---

## Project Workflow

1. Load the housing dataset.
2. Clean the data by removing missing values.
3. Engineer a new **Age Category** feature from the construction year.
4. Encode categorical variables using One-Hot Encoding.
5. Split the dataset into training and testing sets.
6. Train a Decision Tree Regression model.
7. Evaluate the model using:
   - R² Score
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
8. Visualize and interpret the decision tree.
9. Prune the tree for better readability and reduced overfitting.

---

##  Decision Tree

The model predicts house prices by recursively splitting the dataset into smaller groups based on the features that minimize prediction error.

This provides an interpretable model where every prediction follows a clear decision path.

---

##  Features Used

- Area (SqFt)
- Rooms
- Age Category
- Location
- Street Type
- Furnishing
- Property Type
- Has Pool

Target Variable:

- **Price**

---

##  Future Improvements

- Develop an interactive Streamlit web application.
- Compare performance with Random Forest and Gradient Boosting.
- Use a real-world housing dataset.
- Tune model hyperparameters for improved accuracy.

---

## Authors

Caxton Kiptoo
Justus Onyango
