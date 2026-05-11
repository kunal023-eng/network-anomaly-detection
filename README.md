# 🛡️ Network Intrusion Anomaly Detection System

## 📌 Project Overview
An unsupervised machine learning system built to detect abnormal network traffic and potential cyber threats without relying on labeled data. 

By utilizing an **Isolation Forest** algorithm, this model identifies malicious patterns (such as TCP-SYN, Blackhole, and PortScan attacks) purely by analyzing the mathematical distance and behavior of network packets.

## 🛠️ Tech Stack
* **Language:** Python
* **Machine Learning:** Scikit-learn (Isolation Forest)
* **Data Manipulation:** Pandas
* **Visualization:** Matplotlib
* **Environment:** Jupyter Notebook / Google Colab

## 📊 Dataset
The model is trained on the **UNR-IDD (Intrusion Detection Dataset)**, which contains a mix of normal network traffic and various simulated cyber attacks.

## 🚀 Key Results
* Successfully isolated threats without supervised training labels.
* Detected high-risk anomalies, prominently catching **TCP-SYN** and **Blackhole** attacks.
* Filtered out text-based categorical data to create a strictly numerical, distance-based training environment.
