📊 Salary Prediction using XGBoost
📌 Project Overview

This project builds a salary prediction model using the XGBoost Regressor.
The model predicts salaries based on various job-related and demographic features, with a focus on hyperparameter tuning for better accuracy.

🚀 Features

Data preprocessing and feature engineering.

Baseline XGBoost model training.

Hyperparameter tuning with RandomizedSearchCV.

Model evaluation using MAE, MSE, RMSE, and R² Score.

Saving the trained model and predictions to files.

📂 Dataset

The dataset contains:

Features: Job type, education level, experience, and other relevant information.

Target: Salary amount.

📊 Model Performance

Baseline XGBoost Performance:

MAE: 9.467

MSE: 169.694

RMSE: 13.027

R² Score: 0.769

After Hyperparameter Tuning:

Improved accuracy and reduced error metrics.

🔄 Project Workflow
graph TD
    A[Load Dataset] --> B[Data Preprocessing]
    B --> C[Feature Engineering]
    C --> D[Train-Test Split]
    D --> E[Baseline XGBoost Model]
    E --> F[Hyperparameter Tuning with RandomizedSearchCV]
    F --> G[Evaluate Model]
    G --> H[Save Model & Predictions]
    H --> I[Generate Final Report]

🛠️ Installation & Usage
# Clone the repository
git clone https://github.com/your-username/salary-prediction-xgboost.git
cd salary-prediction-xgboost

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
jupyter notebook salary_prediction.ipynb

💾 Saved Files

xgboost_tuned_model.pkl → Trained XGBoost model.

xgboost_predictions.csv → Actual vs Predicted salary values.

📌 Requirements

Python 3.8+

pandas

numpy

scikit-learn

xgboost

joblib

📜 License

This project is licensed under the MIT License.
