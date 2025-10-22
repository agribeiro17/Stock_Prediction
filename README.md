# Optiver - Trading At The Close


**Optiver - Trading At The Close** is a project consisting of multiple machine learning models designed to forecast the closing price movements of hundreds of NASDAQ-listed stocks. The idea for this project was inspired by a [Kaggle competition](https://www.kaggle.com/competitions/optiver-trading-at-the-close).

The main goal was not to participate in the competition itself, but to apply and implement machine learning methods learned in class to address a real-world forecasting problem.

The four models developed and evaluated in this project were: **LSTM, KNN, Linear Regression, and Random Forest.**

This work was part of the **Machine Learning (APC)** course in the **Master’s program in Electrical and Computer Engineering**  at [FEUP](https://sigarra.up.pt/feup/en/ucurr_geral.ficha_uc_view?pv_ocorrencia_id=558417). The project was completed on **December 3, 2023**.


This course provides a comprehensive introduction to Machine Learning, covering both theoretical foundations and practical applications through hands-on projects. Students learn to design, implement, and evaluate learning models while developing teamwork, analytical thinking, and self-directed learning skills.

## 🧠 Technologies Used

- **Python** – main programming language for all data processing and modeling tasks

- **Pandas & NumPy** – for time series manipulation, feature construction, and dataset restructuring

- **Scikit-learn** – for regression modeling (KNN, Random Forest), preprocessing, evaluation (MAE, MSE, RMSE), and hyperparameter tuning with GridSearchCV

- **TensorFlow / Keras** – used for building and training the LSTM model for sequential data learning

- **Matplotlib & Seaborn** – for correlation analysis, exploratory visualization, and performance plots

- **Feature Engineering** – generation of lag-based features and construction of complete stock–date–time combinations using MultiIndexing

- **Model Comparison** – performance evaluation and benchmarking across KNN, LSTM, and Random Forest models

- **Cross-Validation & Optimization** – applied to tune hyperparameters and assess generalization performance

- **Performance Metrics** – included MAE, MSE, and RMSE for quantitative model evaluation

## 📄 Report

A detailed report for this project can be found here: [Optiver Report](https://drive.google.com/file/d/1DVMGCJx-15krngVmtu-hRGlwvaYODCM1/view?usp=sharing), or the `pdf` folder within this repository. The report includes a full explanation of the methodology, results, and conclusions drawn from the experiments.
