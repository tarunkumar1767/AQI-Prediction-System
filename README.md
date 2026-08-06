
# 🚀 AQI Prediction System

> **A Transformer-based Air Quality Index (AQI) Forecasting System** built from scratch using PyTorch for accurate time-series prediction of air quality using historical pollution and meteorological data.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=for-the-badge&logo=pytorch)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📖 Overview

AQI Prediction System is an end-to-end deep learning project that predicts future Air Quality Index (AQI) values from historical environmental observations. The project covers the complete ML lifecycle including preprocessing, exploratory data analysis, feature engineering, Transformer-based forecasting, and regression evaluation.

---

## 📸 Screenshots

|-----------------|---------------------|
| <img src="images/dataset.png" width="450"> | <img src="images/dataset-info.png" width="450"> |

---

## ⭐ Highlights

- End-to-end AQI forecasting pipeline
- Transformer Neural Network for time-series forecasting
- Exploratory Data Analysis (EDA)
- Correlation Heatmap visualization
- Missing value analysis
- IQR-based outlier detection
- ADF stationarity testing
- Date & cyclical feature engineering
- One-Hot Encoding for regions
- MinMax normalization
- Chronological train-test split
- User-input based AQI prediction
- Evaluation using MAE, RMSE and R² Score

--

## 🧩 Features

| Feature | Status |
|---|:---:|
| Data Cleaning | ✅ |
| Missing Value Analysis | ✅ |
| Histograms | ✅ |
| Correlation Heatmap | ✅ |
| Outlier Detection (IQR) | ✅ |
| ADF Test | ✅ |
| Date Feature Engineering | ✅ |
| Cyclical Encoding | ✅ |
| One-Hot Encoding | ✅ |
| Feature Scaling | ✅ |
| Transformer Model | ✅ |
| AQI Prediction | ✅ |
| Regression Metrics | ✅ |

---

## 🏗️ Architecture

                  Air Quality Dataset
                           │
                           ▼
                  Data Preprocessing
     (Cleaning • Missing Values • Outliers)
                           │
                           ▼
             Exploratory Data Analysis (EDA)
        (Histograms • Correlation Heatmap)
                           │
                           ▼
                Stationarity Testing
            (Augmented Dickey-Fuller Test)
                           │
                           ▼
                 Feature Engineering
        (Date Features + Region Encoding)
                           │
                           ▼
                  Feature Scaling
                     (Normalization)
                           │
                           ▼
            Time-Series Sequence Creation
                           │
                           ▼
               Transformer Neural Network
                           │
                           ▼
                    AQI Prediction
                           │
                           ▼
             Performance Evaluation
          (MAE • RMSE • R² Score)
```


## ⚡ Quick Start

```bash
git clone https://github.com/yourusername/AQI-Prediction-System.git
cd AQI-Prediction-System

python -m venv venv

# Windows
venv\Scripts\activate

# Linux/macOS
source venv/bin/activate

pip install -r requirements.txt

jupyter notebook
```

Open `AQI Prediction System.ipynb` and run all cells.

## 🛠 Tech Stack

- Python
- PyTorch
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Statsmodels
- Jupyter Notebook

## 📁 Project Structure

```text
AQI-Prediction-System/
│
├── AQI Prediction System.ipynb
├── air_quality_health_dataset.csv
├── requirements.txt
├── README.md
└── images/
```

## 📊 Exploratory Data Analysis

- Missing value analysis
- Histograms
- Correlation heatmap
- IQR outlier detection
- Distribution analysis

## 🔬 Feature Engineering

- Datetime parsing
- Day/Month/Year extraction
- Cyclical encoding
- Region one-hot encoding
- Feature scaling
- Sequence generation

## 🤖 Transformer Model

The project uses a Transformer Encoder architecture with self-attention to capture temporal dependencies in AQI data.

## 📈 Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## 🌍 Prediction

The trained model predicts AQI using historical pollution and weather observations and supports user-input forecasting.

## 🚀 Future Improvements

- Streamlit dashboard
- FastAPI deployment
- Live AQI API integration
- Hyperparameter tuning
- Docker
- Multi-city forecasting
- Attention visualization
