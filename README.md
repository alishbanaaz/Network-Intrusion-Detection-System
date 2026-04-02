Network Intrusion Detection System
📌 Overview
This repository contains a high-performance Network Intrusion Detection System (IDS) designed to identify and classify network traffic as either Normal or Anomaly. Using the NSL-KDD dataset, the project implements a variety of machine learning and deep learning models to ensure robust security monitoring.

🚀 Key Features
Multi-Model Evaluation: Implementation and comparison of Logistic Regression, SVM, Decision Trees, Random Forest, KNN, and Naive Bayes.

Deep Learning Integration: Features a specialized LSTM (Long Short-Term Memory) neural network with 128 units and dual Dropout layers for capturing complex temporal patterns.

Advanced Feature Engineering: Utilizes Mutual Information to select the top 20 predictive features and eliminates redundant variables through correlation analysis.

Binary Classification: Successfully maps multiple network attack types into a unified 'abnormal' class for streamlined detection.

🛠️ Tech Stack
Language: Python

Libraries: TensorFlow/Keras, Scikit-learn, Pandas, NumPy

Visualization: Matplotlib, Seaborn

📊 Performance Results
The models demonstrated exceptional accuracy during testing:

Random Forest: Achieved 97.6% Accuracy.

Decision Trees: Achieved 97.3% Accuracy.

LSTM Neural Network: Achieved 98.8% Accuracy with a Precision of 0.99 and Recall of 0.99.

K-Nearest Neighbor: Achieved 96.3% Accuracy.

⚙️ Installation & Usage
Install dependencies: pip install -r requirements.txt.

Run the preprocessing and training script to see model comparisons.

Use the prediction module to classify raw network packets as Normal or Anomaly.
