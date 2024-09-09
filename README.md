# Healthcare Cost Prediction - Machine Learning Models Comparison

## Overview
This project delves deep into **Healthcare Cost Patterns**, focusing on precision through comprehensive data preprocessing and rigorous Exploratory Data Analysis (EDA) to uncover meaningful insights. The approach leverages a combination of powerful machine learning models and a neural network to predict healthcare costs, ensuring robust performance through fine-tuning and validation.

## Key Features
- **Models Used**: XGBoost, AdaBoost, LightGBM, Random Forest, CatBoost, and a custom-designed Neural Network.
- **Hyperparameter Tuning**: Implemented both **Grid Search** and **Random Search** for optimal performance across models.
- **Cross-Validation**: Applied cross-validation techniques to ensure the robustness and generalizability of model performance.
- **Outlier Detection**: Employed univariate methods like **IQR** and **Z-Score**, and multivariate techniques such as **Local Outlier Factor (LOF)** and **Isolation Tree** to identify and handle outliers effectively.
- **Error Visualization**: Analyzed model errors using visual tools to better understand performance.
- **Model Comparison**: Compared the performance of models based on several key metrics, offering insights into the strengths and weaknesses of each algorithm.

## Neural Network Component
- **Architecture**: Designed a multi-layer neural network comprising **Dense layers** with 128, 64, and 32 neurons, incorporating **Dropout layers** to prevent overfitting.
- **Training Strategy**: Utilized **early stopping** to avoid overfitting, along with the **adam optimizer** and **mean_absolute_error** loss function.
- **Performance Metrics**: A custom **R-squared metric** was employed to track model performance.
- **Fine-Tuning**: Applied **GridSearchCV** to fine-tune architecture hyperparameters such as the number of neurons, dropout rates, epochs, and batch sizes.
- **Training**: Trained the neural network for 200 epochs, visualizing both training and validation losses to ensure stability.
- **Comparison with Tree-Based Models**: The neural network's performance was compared to tree-based models, providing a comprehensive evaluation across all approaches.

## Model Performance Comparison
Three top-performing models—**XGBoost**, **LightGBM**, and **Random Forest**—were selected for a final comparison. Here’s a summary of their performance:

- **XGBoost**: Achieved the highest predictive accuracy but had slower training times compared to LightGBM.
- **LightGBM**: Struck an excellent balance between speed and performance, making it ideal for large-scale datasets.
- **Random Forest**: Produced robust predictions but lacked the fine-tuning capabilities of gradient boosting methods.
- **Neural Network**: Demonstrated competitive performance, especially after fine-tuning, and offered insights into potential nonlinear relationships in the data.
