# Fuzzy Histograms on Load Forecasting
This repository contains the source code and research paper for a project that enhances short-term load forecasting (STLF) by integrating fuzzy logic concepts with a deep learning model. The project compares a baseline Bidirectional LSTM model with a hybrid Fuzzy-LSTM model that leverages fuzzy feature engineering and Fuzzy C-Means (FCM) clustering to improve prediction accuracy. The hybrid model demonstrates significantly superior forecasting performance, validating the hypothesis that integrating fuzzy concepts with deep learning can better capture the complex dynamics and uncertainties inherent in electricity load data.

# Key Features
* Hybrid Model Architecture: Implements a novel approach combining Fuzzy Logic, Fuzzy C-Means (FCM) clustering, and a Bidirectional LSTM network.
* Advanced Feature Engineering:
* Fuzzy Features: Transforms crisp inputs (like temperature, time of day, and lagged load) into descriptive linguistic variables (e.g., temp_hot, hour_morning) to capture non-linear relationships.
* FCM Clustering: Identifies typical daily load patterns and uses cluster membership degrees as contextual features for the LSTM.
* Comparative Analysis: Provides a full implementation and direct performance comparison between the hybrid model and a standard Bidirectional LSTM baseline.
*Comprehensive Evaluation: Uses multiple metrics (RMSE, MAE, R², and a custom tolerance-based accuracy) to rigorously evaluate model performance.
* Reproducibility: Includes the full Jupyter Notebook and a detailed research paper, allowing for easy replication and extension of the work.

# Structure
main

├── Fuzzy Histograms on Load Forecasting.pdf

├── Source Code.ipynb

└── README.md
* Fuzzy Histograms on Load Forecasting.pdf: The detailed research paper outlining the project's background, methodology, results, and conclusions.
* Source Code.ipynb: A Jupyter Notebook containing the complete Python code for data preprocessing, model building, training, and evaluation for both the baseline and hybrid models.
* README.md: This file.
