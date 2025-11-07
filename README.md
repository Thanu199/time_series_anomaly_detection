# 🧠 Time Series Anomaly Detection for IoT Sensors

## 📘 Overview
This project focuses on detecting anomalies in **IoT sensor time series data**, which can help identify early signs of equipment failure or maintenance needs in manufacturing systems.  
It includes **data preprocessing**, **feature engineering**, and two distinct **anomaly detection approaches** — one statistical and one deep learning-based — with a full evaluation and visualization of results.


## 🎯 Objectives
- Build an **end-to-end anomaly detection pipeline** for IoT sensor data  
- Handle **missing values, outliers**, and perform **EDA** with visual insights  
- Engineer **rolling statistical features**, **trend indicators**, and **seasonal components**  
- Implement and compare:
  - **Approach 1:** Statistical/Unsupervised model (e.g., Isolation Forest / Z-score / LOF)
  - **Approach 2:** Deep Learning model (e.g., Autoencoder / LSTM)
- Evaluate model performance using **precision, recall, F1-score, AUC-ROC** (where applicable)
- Visualize detected anomalies in context  

## 📂 Repository Structure
time_series_anomaly_detection/
│
├── time_series_anomaly_detection.ipynb   # Main Jupyter notebook
├── data/                                 # Dataset folder
│   └── dataset.csv
├── models/                               # Saved model files (if any)
│   └── model.pkl
├── README.md                             # Project documentation
└── requirements.txt                      # List of dependencies

## 🧰 Tech Stack
- **Programming Language:** Python 3.x  
- **Libraries:**  
  - Data: `pandas`, `numpy`, `scipy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Modeling: `scikit-learn`, `tensorflow` or `pytorch`
  - Utilities: `logging`, `argparse`, `os`, `joblib`
 
## ⚙️ Installation

- Instructions for users to run your project locally.

### Clone the repository
- git clone https://github.com/Thanu199/time_series_anomaly_detection.git

### Navigate to the folder
- cd time_series_anomaly_detection

### Install dependencies
- pip install -r requirements.txt


---

## 🚀 Usage

### Open the Jupyter notebook
- jupyter notebook time_series_anomaly_detection.ipynb
 
## 👤Author
- Thanusri
- AI/ML Engineer (Fresher) | Data Science Enthusiast
- sriithanu472@gmail.com
