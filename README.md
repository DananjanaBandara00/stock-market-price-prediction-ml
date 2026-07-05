# stock-market-price-prediction-ml
Predicting next-day stock prices using machine learning models and historical Yahoo Finance data through preprocessing, feature engineering, model training, and comparative performance evaluation.

##  Project Overview

This project presents an end-to-end machine learning solution for predicting next-day stock prices using historical financial market data obtained from Yahoo Finance.

The project follows a complete machine learning workflow, including data collection, preprocessing, exploratory data analysis (EDA), feature engineering, model development, hyperparameter tuning, and performance evaluation.

Six machine learning models were implemented and compared to determine the most accurate approach for stock price prediction. The final evaluation identified the LightGBM Regressor as the best-performing model based on multiple regression and classification metrics.

## Objectives

- Predict next-day stock prices using historical market data.
- Perform comprehensive data preprocessing and exploratory data analysis.
- Engineer technical features to improve prediction accuracy.
- Implement and compare multiple machine learning models.
- Evaluate model performance using standard regression and classification metrics.
- Identify the most suitable model for stock market forecasting.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab
- LightGBM
- XGBoost
- TensorFlow / Keras
- PyTorch
- Jupyter Notebook

  ##  Machine Learning Models

The following machine learning models were implemented and evaluated during this project:

- 🌳 Random Forest Regressor
- 🚀 XGBoost Regressor
- ⚡ LightGBM Regressor
- 📈 Support Vector Regressor (SVR)
- 🧠 Artificial Neural Network (ANN)
- 🔄 Long Short-Term Memory (LSTM)

Each model was trained using the same preprocessed dataset and evaluated using consistent validation techniques to ensure a fair performance comparison.

## Model Evaluation

The models were evaluated using multiple regression and classification metrics:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Accuracy
- F1 Score
- Area Under the ROC Curve (AUC)

Hyperparameter tuning and cross-validation techniques were applied to improve model performance and reduce overfitting.

## Results

| Model | Best Version | R² Score |
|--------|-------------|----------|
| LightGBM Regressor | Tuned GridSearchCV | **0.9982** |
| Random Forest Regressor | Baseline Model | 0.9812 |
| XGBoost Regressor | All Features Variant | 0.9724 |
| Support Vector Regressor | Tuned RBF Kernel | 0.9626 |
| Artificial Neural Network | Best ANN Version | 0.8779 |
| Long Short-Term Memory | Deeper LSTM | Evaluated |

##  My Contribution

This project was completed as a **six-member team project**.

My primary contributions included:

- Performed date conversion and chronological sorting of historical stock market data for time-series analysis.
- Implemented the Random Forest Regressor for next-day stock price prediction.
- Developed multiple Random Forest model variants and performed hyperparameter tuning.
- Applied TimeSeriesSplit validation to evaluate model performance.
- Participated in model evaluation and comparison with other machine learning approaches.

  ##  Team

This project was completed collaboratively by a six-member team as part of the Artificial Intelligence and Machine Learning module at the Sri Lanka Institute of Information Technology (SLIIT).

Each member was responsible for implementing specific preprocessing techniques and machine learning models, which were integrated into the final solution.

##  Future Improvements

- Integrate real-time stock market data.
- Incorporate financial news sentiment analysis.
- Explore Transformer-based forecasting models.
- Develop an interactive web dashboard for live predictions.
- Deploy the model using cloud services for real-time inference.

 ##  Acknowledgements

This project was developed as part of the **IT2011 – Artificial Intelligence and Machine Learning** module at the Sri Lanka Institute of Information Technology (SLIIT). 
  
