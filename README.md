# Healthcare Cost Prediction - Machine Learning Models Comparison

## Overview
With a dedicated emphasis on precision, this project meticulously explores **Healthcare Cost Patterns** through extensive data preprocessing and rigorous Exploratory Data Analysis (EDA), unearthing invaluable insights. The project leverages a suite of powerful machine learning models to predict healthcare costs, ensuring robust performance through thorough tuning and validation processes.

## Key Features
- **Models Used**: XGBoost, AdaBoost, LightGBM, Random Forest, CatBoost.
- **Hyperparameter Tuning**: Implemented both **Grid Search** and **Random Search** for fine-tuning model performance.
- **Cross-Validation**: Ensured robust model performance using cross-validation techniques.
- **Outlier Detection**: Applied both univariate methods like **IQR** and **Z-Score**, and multivariate techniques like **Local Outlier Factor (LOF)** and **Isolation Tree** to detect and handle outliers in the dataset.
- **Error Visualization**: Visualized and analyzed model errors to gauge performance.
- **Model Comparison**: Compared models based on their performance across several key metrics, offering a thorough analysis of each algorithm's strengths and weaknesses.

## Model Performance Comparison
Three models, **XGBoost**, **LightGBM**, and **Random Forest**, were selected for a final comparison. Each model was evaluated on its ability to predict healthcare costs with precision, speed, and generalizability across different cross-validation folds. Here's a brief summary of the key differences:
- **XGBoost**: Excelled in predictive accuracy but was slower in training compared to LightGBM.
- **LightGBM**: Offered a great balance between speed and performance, making it ideal for large datasets.
- **Random Forest**: Provided robust results but lacked the fine-tuning capabilities of gradient boosting models.

## How to Run
1. Clone the repository.
   ```bash
   git clone https://github.com/your-repo/healthcare-cost-prediction.git
