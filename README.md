# Rainfall_Nowcasting
This repository provides implementation of rainfall nowcasting using LSTM-based models (Stacked, Encoder–Decoder, Autoencoder) with multi-sensor data fusion. Weather station, GNSS, radar, and lightning data are combined to enhance short-term forecasts in tropical coastal regions.
Description:
This repository contains the implementation, data preprocessing workflows, and evaluation scripts for rainfall nowcasting using advanced LSTM-based architectures (Stacked LSTM, Encoder–Decoder LSTM, and Autoencoder LSTM). The study leverages multi-sensor data fusion combining Weather Station (WS), GNSS-derived tropospheric delays, weather radar reflectivity, and lightning observations to improve short-term rainfall forecasts in tropical coastal regions.

Key Features:

📊 End-to-end pipeline for rainfall data preprocessing (time series cleaning, scaling, feature engineering).

🔗 Multi-sensor fusion framework integrating GNSS, radar, lightning, and AWS datasets.

🧠 Implementation of three deep learning models:

Stacked LSTM

Encoder–Decoder LSTM

Autoencoder LSTM

⚡ Evaluation using regression metrics (RMSE, MAE, R²) and event-detection metrics (FAR, CSI, Precision, Recall, F1).

📉 Visualization scripts for loss curves, prediction vs. actual rainfall, and feature contribution analysis.

Repository Structure:

├── data/                # Data input (placeholder, not shared due to agreements)
├── preprocessing/        # Scripts for data cleaning and feature engineering
├── models/               # LSTM model definitions
├── training/             # Training scripts with early stopping
├── evaluation/           # Metrics computation and visualization
├── figures/              # Generated plots for publication
└── README.md             # Project overview


Note on Data Availability:
The raw datasets used in this study were provided through collaborations and MoUs with IITM Pune, IMD, ECMWF, and ISRO GNSS stations. Due to data sharing restrictions, the raw data cannot be redistributed through this repository. Interested researchers may directly contact the respective agencies for access.
