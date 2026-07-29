# VedGrow_ML_O2 - 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview
This project predicts house sale prices using the Ames Housing dataset. It includes complete data preprocessing, feature engineering, model training, evaluation, and visualization. Multiple regression algorithms are compared to identify the best-performing model.

---

## 🎯 Objectives
- Clean and preprocess the housing dataset
- Handle missing values and outliers
- Perform feature engineering
- Select important features
- Train multiple regression models
- Compare model performance
- Visualize feature importance and prediction results

---

## 📂 Dataset
Dataset: AmesHousing.csv

Target Variable:
- SalePrice

Features include:
- Overall Quality
- Living Area
- Garage Area
- Year Built
- Bathrooms
- Basement Area
- Lot Size
- And many more housing-related attributes

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 📚 Machine Learning Workflow

### 1. Data Loading
- Load the Ames Housing dataset
- Explore the dataset
- Check missing values
- Generate descriptive statistics

### 2. Data Cleaning
- Handle missing values
- Remove outliers using the IQR method

### 3. Feature Engineering
Created new features such as:
- HouseAge
- TotalBath

### 4. Feature Encoding
- One-Hot Encoding for categorical variables

### 5. Feature Selection
- Correlation-based feature selection

### 6. Data Splitting
- 80% Training
- 20% Testing

### 7. Feature Scaling
- StandardScaler

### 8. Models Trained
- Linear Regression
- Ridge Regression
- Random Forest Regressor

### 9. Model Evaluation
Performance metrics:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

### 10. Visualization
- Feature Importance
- Actual vs Predicted Prices
- Residual Plot

---

## 📈 Results
The project compares multiple regression algorithms and identifies the best-performing model based on evaluation metrics.

---

## 📁 Project Structure

House-Price-Prediction/
│
├── Model.ipynb
├── dataset
│      ├── AmesHousing.csv
│      ├── test.csv
│      └── train.csv
├── README.txt
└── requirements.txt

---

## ▶️ How to Run

1. Clone the repository

git clone https://github.com/your-username/House-Price-Prediction.git

2. Install required libraries

pip install -r requirements.txt

3. Open Jupyter Notebook

jupyter notebook

4. Run all cells in Model.ipynb

---

## 📦 Required Libraries

numpy
pandas
matplotlib
scikit-learn

Install using:

pip install numpy pandas matplotlib scikit-learn

---

## 🚀 Future Improvements
- Hyperparameter tuning
- XGBoost and LightGBM implementation
- Model deployment using Streamlit or Flask
- Cross-validation
- Interactive dashboard

---

## 👨‍💻 Author

Shivam Kumar Jha

---

⭐ If you found this project useful, consider giving the repository a Star on GitHub!
