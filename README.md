# 🧠 AutoEncoder for Anomaly Detection

This repository provides a Jupyter Notebook implementation of an AutoEncoder (AE) model designed for anomaly detection tasks. AutoEncoders learn a compressed representation of data and are trained to reconstruct it, making them effective for detecting outliers based on reconstruction error....

---

## 📌 Overview

- Trains an AutoEncoder neural network on normal data
- Detects anomalies based on reconstruction loss
- Visualizes training performance and error distribution
- Can be extended to real-world datasets (e.g., manufacturing, finance, or healthcare)

---

## 📁 Files

```
.
├── AE.ipynb
├── articles_df.csv
├── interactions_full_df.csv
└── interactions_train_df.csv

0 directories, 4 files
```

---

## 🧪 How to Run

1. **Clone this repo:**

```
git clone https://github.com/WizHabasi/AE.git
cd AE
```
2. Install Dep
```
pip install -r requirements.txt
```
## Model Architecture
 - Encoder: Compresses input features into a lower-dimensional latent space
 - Decoder: Reconstructs the original input from latent representation
 - Loss Function: Mean Squared Error (MSE)
 - Anomaly Score: High reconstruction error indicates potential anomaly


