# Movie Popularity Prediction

A Linear Regression project to predict **movie revenue/popularity** using TMDB dataset.  
This project explores data analysis, feature engineering, and machine learning modeling.

---

## 📂 Dataset
- Dataset: [TMDB Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- Number of movies: 3000 entries
- Features include: `budget`, `popularity`, `runtime`, `release_year`, `release_month`, `genres`, `original_language`, `status`, `revenue`

---

## 🔍 Project Steps

1. **Data Loading & Cleaning**  
   - Handle missing values  
   - Extract features like release year/month  

2. **Feature & Target Selection**  
   - Features: `budget`, `popularity`, `runtime`, `release_year`, `release_month`  
   - Target: `revenue`  

3. **Train/Test Split**  
   - 80% training, 20% testing  

4. **Linear Regression Model**  
   - Train a model to predict revenue  

5. **Evaluation Metrics**  
   - Mean Squared Error (MSE)  
   - Root Mean Squared Error (RMSE)  

6. **Visualization**  
   - **Revenue Distribution**  
   - **Movies by Language (Top 5)**  
   - **Top 5 Genres**  
   - **Movie Status (Released/Unreleased)**  
   - **Feature Importance**  
   - **Actual vs Predicted Revenue**  
   - **Residual Plot**  
