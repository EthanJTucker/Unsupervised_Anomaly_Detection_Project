# Unsupervised Anomaly Detection Project
Project in which I perform unsupervised anomaly detection with various ML approaches. Project is created to (1) introduce myself to anomaly detection on time-series data, and (2) act as a work sample for NREL during my interview on 10/5/2022.

[Data Source](https://raw.githubusercontent.com/numenta/NAB/master/data/realKnownCause/machine_temperature_system_failure.csv)

ML models used for anomaly detection: 

1. Principal Component Analysis (PCA)

2. K-Means

3. Isolation Forest

4. LSTM Autoencoder (RNN)

Best models by f1 score were PCA and K-Means with ~ 500 anomalies detected. At 700 models we have a more robust detection of a difficult to detect anomaly at the cost of lower precision. 600 is a good middle ground.
