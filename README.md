# Movie Rating Prediction with Python  

##  Project Overview  
This project focuses on predicting **movie ratings** using machine learning models.  
The dataset was obtained from [Kaggle](https://www.kaggle.com/code/akash1vishwakarma/movie-rating-prediction-with-python), and the goal is to analyze different movie-related features to estimate ratings more accurately.  

Through this project, I explored **data preprocessing, exploratory data analysis (EDA), regression models, and evaluation metrics** to build a complete prediction pipeline.  

---

## ⚙️ Tools & Libraries Used  
- **Python**  
- **Pandas, NumPy** – Data processing  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-Learn** – Machine Learning models  
- **Jupyter Notebook / Google Colab** – Development environment  

---

## 🔍 Workflow  

1. **Data Preprocessing**
   - Handling missing values  
   - Encoding categorical features  
   - Feature scaling  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of ratings  
   - Correlation heatmaps  
   - Visualizations of key features  

3. **Modeling**
   - Linear Regression  
   - Random Forest Regressor  
   - XGBoost (optional)  

4. **Evaluation Metrics**
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - R² Score  

---

##  Results  

Here are the performance metrics of different machine learning models tested:  

| Model                        | Accuracy (%) | RMSE  |
|-------------------------------|--------------|-------|
| Linear Regression             | 10.56        | 1.26  |
| Random Forest                 | 38.91        | 1.04  |
| Decision Tree                 | -20.64       | 1.47  |
| Extreme Gradient Boosting (XGBoost) | 36.00        | 1.07  |
| Gradient Boosting             | 40.21        | 1.03  |
| LightGBM (Light Gradient Boosting) | **42.65**   | **1.01** |
| CatBoost                      | ...          | ...   |
| K-Nearest Neighbors (KNN)     | 1.97         | 1.32  |

 **Best Model:**  
**Light Gradient Boosting (LightGBM)** achieved the highest accuracy (**42.65%**) and the lowest RMSE (**1.01**).  
