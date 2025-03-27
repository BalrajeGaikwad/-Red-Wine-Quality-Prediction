# -Red-Wine-Quality-Prediction
This project aims to predict the quality of red wine using machine learning models. We implement Random Forest for classification and regression, applying Grid Search CV for hyperparameter tuning to achieve optimal model performance.


🚀 Project Overview
The Red Wine Quality dataset contains physicochemical properties of different red wine samples, along with their quality ratings. Using machine learning models, we analyze and predict wine quality based on these features.

📌 Key Features
✔ Uses the Red Wine Quality Dataset from UCI Machine Learning Repository
✔ Implements Random Forest for classification & regression
✔ Applies Grid Search CV for hyperparameter tuning
✔ Performs feature selection and importance analysis
✔ Evaluates models using various metrics

📊 Tech Stack & Libraries Used
Python 🐍

scikit-learn (for machine learning models & hyperparameter tuning)

Matplotlib & Seaborn (for data visualization)

Pandas & NumPy (for data preprocessing)

🔍 Machine Learning Approach
✅ 1. Data Preprocessing
Handling missing values

Feature scaling & transformation

Exploratory Data Analysis (EDA)

✅ 2. Model Implementation
Random Forest for Classification & Regression

✅ 3. Hyperparameter Tuning using Grid Search CV
Optimizing key parameters:

Number of trees (n_estimators)

Max depth (max_depth)

Minimum samples split (min_samples_split)

✅ 4. Model Evaluation
Classification Metrics: Accuracy, Precision, Recall, F1-Score

Regression Metrics: RMSE, MAE, R² Score

📈 Results & Insights
✔ Hyperparameter tuning improves model accuracy and generalization
✔ Some features (e.g., alcohol content, acidity) are highly correlated with wine quality
✔ The model can be used for quality assessment and wine grading
