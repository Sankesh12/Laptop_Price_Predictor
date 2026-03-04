# 💻 Laptop Price Predictor

- A Machine Learning based web application that predicts laptop prices based on configuration details.

# 🚀 Project Overview

- This project uses Data Analysis, Feature Engineering and supervised Machine Learning techniques to predict laptop prices based on hardware specifications.

- The model is trained on a Laptop Price Dataset and deployed using Streamlit for real-time predictions.

# 🛠 Technologies Used

- Python

- Pandas

- NumPy

- Seaborn

- Matplotlib

- Scikit-learn

- XGBoost

- Streamlit

- Pickle

# 🤖 Machine Learning Models Used

- Linear Regression

- Ridge Regression

- Lasso Regression

- K-Nearest Neighbors (KNN)

- Decision Tree Regressor

- Random Forest Regressor

- Extra Trees Regressor

- AdaBoost Regressor

- Gradient Boosting Regressor

- XGBoost Regressor

- Voting Regressor

- Stacking Regressor

# 📊 Dataset Details

- Dataset: Laptop Price Dataset

- Source: Kaggle

- Target Variable: Price

- Problem Type: Regression

# Features Included:

- Company

- TypeName

- RAM

- Weight

- Touchscreen

- IPS Display

- Screen Resolution

- CPU

- GPU

- HDD

- SSD

- Operating System

# 🔍 Methodology
## 1️⃣ Data Cleaning

- Removed duplicate rows

- Checked missing values

- Dropped unnecessary columns

- Converted RAM & Weight into numeric format

## 2️⃣ Feature Engineering

- Extracted Touchscreen and IPS features

- Calculated PPI (Pixels Per Inch)

- Simplified CPU brands (Intel i3/i5/i7, AMD, Others)

- Split Storage into HDD and SSD

- Categorized Operating Systems (Windows, Mac, Others)

- Applied log transformation on Price

## 3️⃣ Encoding & Pipeline

- Used ColumnTransformer

- Applied OneHotEncoder

- Built complete ML Pipeline using Scikit-learn

# 📈 Model Evaluation
## Evaluation Metrics Used:

- R2 Score

- Mean Absolute Error (MAE)

# 🏆 Best Performing Models

- Random Forest

- Extra Trees

- Gradient Boosting

- Stacking Regressor

✅ Ensemble models performed better than simple linear models.

# 💡 Key Insights

- Price strongly depends on RAM, SSD, CPU, GPU, and PPI

- Log transformation improved performance

- Feature engineering significantly boosted accuracy
- Ensemble techniques provided the best results

# 🌐 Deployment

- Final model saved using Pickle

- Integrated into a Streamlit web app

## Users Can:

- Select laptop brand

- Choose specifications

- Click Predict Price

- Get instant predicted price

# ▶️ How to Run the Project
- #Install dependencies
- pip install -r requirements.txt

- #Run the Streamlit app
- streamlit run app.py

# 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV

- Add Cross-Validation

- Deploy on Streamlit Cloud

- Add visualization dashboard

- Add feature importance graph

- Try Deep Learning models
