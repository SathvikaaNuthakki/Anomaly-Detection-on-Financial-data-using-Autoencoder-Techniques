# Anomaly-Detection-on-Financial-data-using-Autoencoder-Techniques
# Overview

This project focuses on anomaly detection using autoencoders, a type of neural network designed for unsupervised learning. The autoencoder is trained on normal data to learn its patterns and reconstruct them. Any significant deviation in reconstruction error is identified as an anomaly.

# Features

1.Uses deep learning-based autoencoders for anomaly detection.

2.Learns normal data patterns and identifies deviations as anomalies.

3.Implements data preprocessing and visualization.

4.Built using Python and deep learning libraries.

# Algorithms and Technologies

Algorithms: 

1.Autoencoder-based anomaly detection

2.Reconstruction error thresholding

3.Normalization and data preprocessing techniques

4.Isolation Forest
  
5.XG Boost

# Technologies:

1.Python

2.TensorFlow/Keras

3.NumPy & Pandas

4.Matplotlib & Seaborn

5.Jupyter Notebook

# Dataset Information

The dataset used for this project is sourced from Kaggle, titled “Bank Transaction Fraud Detection”. It consists of 200,000 financial transactions, specifically curated to identify fraudulent banking activities and enhance digital transaction security.

This dataset includes various transaction attributes such as Customer ID, Transaction ID, Transaction Amount, Merchant Category, Location Data, Timestamp, Device Type, and Fraud Labels (0 for legitimate, 1 for fraud).

By incorporating multiple features related to user transactions, this dataset helps build a robust anomaly detection model. The diverse range of transaction behaviors ensures accurate fraud detection while minimizing false positives and false negatives.

For effective model training and evaluation, the dataset is split into three sets:

Training Set (70%): 140,000 transactions used for training the autoencoder.

Validation Set (20%): 40,000 transactions to fine-tune the model.

Test Set (10%): 20,000 transactions to assess performance.

This dataset is useful for training an anomaly detection model as it includes both normal and fraudulent transactions.

The dataset can be accessed by using the link : https://www.kaggle.com/datasets/marusagar/bank-transaction-fraud-detection?resource=download

# Steps for Project Execution

1.Data Collection: Gather and preprocess the dataset.

2.Data Preprocessing: Normalize and split data into training and testing sets.

3.Model Building: Design and train the autoencoder using TensorFlow/Keras.

4.Anomaly Detection: Compute reconstruction errors and set an anomaly threshold.

5.Evaluation: Visualize and analyze model performance.

# Project Workflow

1.Load the dataset.

2.Perform data preprocessing (normalization, splitting).

3.Build and train the autoencoder model.

4.Compute reconstruction errors.

5.Set threshold and detect anomalies.

6.Visualize results and evaluate performance.

7.Optimize and fine-tune the model for better accuracy.


