# Flight Fare Prediction

## 📌 Project Description

Flight Fare Prediction is a machine learning project that leverages historical flight fare data from various airlines to predict ticket prices for new data. The project involves:

- **Data Cleaning:** Handling missing values, removing outliers, and preprocessing features.
- **Data Analysis:** Identifying key factors that impact ticket prices through bi-variate analysis.
- **Feature Engineering:** Applying One-Hot Encoding and Target Encoding Techniques.
- **Model Training:** Training multiple models, including **Random Forest**, **Linear Regression**, and **Decision Tree Regression**, to determine the best-performing model.
- **Model Evaluation:** Assessing model performance using **R² score, Mean Squared Error (MSE), Mean Absolute Error (MAE), and Mean Absolute Percentage Error (MAPE)**.
- **Hyperparameter Tuning:** Fine-tuning the model using **RandomizedSearchCV** to improve performance.

## 🛠 Tech Stack

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

## 📊 Usage

- Execute the cells step by step in Jupyter Notebook or run the script in any Python-supported IDE to preprocess data, train models, and       evaluate performance.
- Modify hyperparameters in the `RandomizedSearchCV` section to experiment with different tuning strategies.

## 🔥 Results

Based on evaluation metrics, **Random Forest** was the best-performing model, showing superior accuracy over other models, such as Linear Regression and Decision Tree.

