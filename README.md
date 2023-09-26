# LSTM Model for Predicting Sunspots 
This project focuses on analyzing sunspot activity and designing, training, evaluating and predicting sunspot counts using LSTM, GRU, and Bidirectional LSTM models.  It analyzes 73,718 daily observations of sunsposts from 1818 to 2019.

## Skills Used:
This project used a variety of data analysis skills including: data handling, time series analysis (understanding of time series data, given that sunspot observations are sequential, & capturing and leveraging patterns over time for predictive modeling), deep learning and neural network modelling (building LSTM models, GRU models, and BiLSTM models), model regularization and evaluation, hyperparameter optimization, model performance evaluation, and results interpretation.

## Project Summary:

**Goal:**
This project focused on analyzing sunspot activity and designing, training, evaluating and predicting sunspot counts using LSTM, GRU, and Bidirectional LSTM models. Sunspots are studied because their activity has implications in solar radiation and can affect space and terrestrial communication.  The goal of this project is to process and analyze historic sunspot dataset, and develop, tune, and evaluate LSTM, GRU, and BiLSTM models.

**Dataset Overview:**
73,718 daily observations from 1818 to 2019.

## Key Procedures:
**Data Handling:**
* Loaded and analyzed data.
* Split into training and test sets.

**Model Construction & Evaluation:**
* Developed LSTM, GRU, and BiLSTM models.
* Implemented early stopping.
* Optimized using Keras Tuner.
* Assessed models using RMSLE and RMSE.

**Performance:**
* LSTM: RMSLE=0.5989, RMSE=14.0529.
* GRU: RMSLE=0.6110, RMSE=14.3250.
* BiLSTM: RMSLE=0.5850, RMSE=13.9200.

**Optimized Models:**
* LSTM: 160 units, dense layers (224, 160).
* GRU: 140 units, dense layers (200, 140).
* BiLSTM: 150 bidirectional units, dense layers (220, 150).

## Conclusions
* All models proved effective in capturing the sequential patterns in sunspot activity, given their recurrent nature.
* While all models—LSTM, GRU, and Bidirectional LSTM—provided close performances, the Bidirectional LSTM model achieved slightly better results in terms of RMSLE and RMSE.
* Hyperparameter tuning was essential for extracting the best performance from each model type.
* Sunspot activity's sequential nature makes RNN architectures apt for predictions, but the choice between LSTM, GRU, and Bidirectional LSTM would depend on specific project constraints and requirements.
