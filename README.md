

This project is for academic and demonstration purposesز

---

# 🚀 LSTM-Based Network Intrusion Detection System (NIDS)

This project implements a Network Intrusion Detection System (NIDS) using a Long Short-Term Memory (LSTM) deep learning model to detect Denial of Service (DoS) attacks. The model is trained and evaluated using the NSL-KDD dataset and achieves high accuracy in identifying various types of network attacks.

## 📌 Abstract

The existence of vulnerabilities in programs and systems allows attackers to exploit and launch DoS attacks. This research designs an LSTM model that analyzes network traffic to detect potential DoS attacks by leveraging temporal patterns using recurrent neural networks. The LSTM model was trained on the NSL-KDD dataset, containing multiple types of attacks including DoS, U2R, R2L, and Probe. With its ability to capture long-range dependencies, the model achieved **99.9% accuracy in detecting DoS attacks** and **98.4% for other attacks**.

---

## 📖 Table of Contents

- [Background](#background)
- [Problem Overview](#problem-overview)
- [Aims and Objectives](#aims-and-objectives)
- [Existing Methods](#existing-methods)
- [Methodology Overview](#methodology-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#-license)

---

## 🔍 Background

Network Intrusion Detection Systems (NIDS) are crucial for monitoring traffic and identifying malicious activities. LSTM models are particularly well-suited for recognizing patterns in sequential data like network traffic, making them effective for DoS detection.

---

## ❗ Problem Overview

The presence of vulnerabilities allows attackers to launch DoS attacks that disrupt services. These attacks can have various motives, and with the growth of internet-connected systems, their frequency is expected to increase.

---

## 🎯 Aims and Objectives

- Understand key NIDS concepts.
- Design a system to detect DoS attacks.
- Analyze DoS attack patterns.
- Build and train an accurate LSTM model.
- Enable real-time alerting for detected threats.

---

## 📚 Existing Methods

| Study | Model | Accuracy | Drawback |
|------|-------|----------|----------|
| LSTM for NIDS | LSTM | 99.93% | Long training time |
| Sampling-based NIDS | LSTM + CNN | 99.20% | Requires large labeled data |
| Autoencoder-based | Autoencoder | 98.73% | Complex for large data |
| Deep Learning NIDS | DDN | 99.40% | Poor generalization |
| GMM-based Detection | GMM | 94% | Resource intensive |

---

## 🛠️ Methodology Overview

1. **Data Preparation:** Clean and filter the NSL-KDD dataset.
2. **Model Construction:** Create the LSTM model for sequence learning.
3. **Training:** Train on labeled traffic data.
4. **Detection:** Predict incoming traffic as normal or attack.
5. **Evaluation:** Use metrics like accuracy, precision, and recall.

---

## 🗂️ Dataset

- **Name:** NSL-KDD
- **Attack Types:** DoS, U2R, R2L, Probe
- **Source:** [NSL-KDD Dataset](https://www.unb.ca/cic/datasets/nsl.html)

---

## 🧠 Model Architecture

- **Layers:** LSTM, Dense, Dropout
- **Loss Function:** Categorical Crossentropy
- **Optimizer:** Adam
- **Evaluation Metrics:** Accuracy, Confusion Matrix

---

## 📊 Results

| Attack Type | Accuracy |
|-------------|----------|
| DoS         | 99.9%    |
| Others      | 98.4%    |

---

## 🧾 Conclusion

This LSTM-based NIDS effectively detects DoS attacks with high accuracy. It provides a strong foundation for future enhancements, such as deploying the model in real-time network monitoring environments or integrating with other security tools.

---

> Built with ❤️ by Mawdah

## 📃 License

This project is for academic and demonstration purposes. For commercial use, please contact the developer.
