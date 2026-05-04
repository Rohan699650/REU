# Lightweight Real-Time Intrusion Detection for IoT Networks using TSANet

A lightweight **real-time Intrusion Detection System (IDS)** for IoT networks deployed on **Raspberry Pi 5** using a custom **Temporal-Spatial Attention Network (TSANet)** architecture for low-latency attack detection.

---

## Features
- Real-time network traffic monitoring  
- Lightweight deep learning model for edge devices  
- CNN-based spatial feature extraction  
- LSTM-based temporal learning  
- Spatial + temporal attention mechanisms  
- Model pruning and quantization for optimization  
- Raspberry Pi deployment  
- Live attack detection with alert generation  

---

## Problem Statement
Traditional IDS systems are often deployed on cloud/server infrastructure and are too computationally expensive for IoT edge devices. This project focuses on building a lightweight IDS capable of performing real-time intrusion detection directly on resource-constrained hardware.

---

## Tech Stack
- Python  
- PyTorch  
- Scapy  
- Pandas  
- NumPy  
- Scikit-learn  
- Raspberry Pi 5  
- TorchScript  

---

## Dataset
**CICIDS2017 Dataset**

### Attack Classes Detected
- Benign  
- Bot  
- Brute Force  
- DDoS  
- DoS  
- Heartbleed  
- Infiltration  

---

## Model Architecture
TSANet combines:

- **1D CNN** → Spatial feature extraction  
- **Spatial Attention Layer** → Important feature selection  
- **LSTM** → Temporal sequence learning  
- **Temporal Attention Layer** → Important time-step selection  
- **Feature Fusion** → Final classification  

---

## Deployment Pipeline
Packet Capture → Flow Reconstruction → Feature Extraction → Preprocessing → Model Inference → Alert Generation
---

## Results
- **98.3% Offline Accuracy**
- **96.8% Real-Time Accuracy**
- **8–12 ms inference latency per flow**

---

## Research Paper
This project resulted in a research publication:

**"Lightweight Real-Time Intrusion Detection for IoT Networks Using TSANet Deployed on Raspberry Pi with Live Traffic Monitoring"**

---

## Future Improvements
- Improve rare attack detection  
- Handle class imbalance using SMOTE  
- Evaluate on UNSW-NB15 and IoT-23 datasets  
- Expand deployment to larger IoT environments  

---

## Author
**Rohan Kulkarni**  
AI/ML | Cybersecurity | IoT Security | Edge AI Research
