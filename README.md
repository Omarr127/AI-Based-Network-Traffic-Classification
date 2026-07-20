# 🛡️ Cybersecurity Anomaly Detection System using Machine Learning

A machine learning-based intrusion detection system designed to identify and classify different types of cyberattacks from network traffic data. The project implements and compares multiple ML algorithms to detect malicious activities and distinguish between normal and attack behaviors.

The system classifies network traffic into five categories:

- ✅ Normal Traffic
- 🔴 Denial of Service (DoS)
- 🟠 Probe Attacks
- 🟡 Remote to Local (R2L)
- 🟣 User to Root (U2R)

---

# 📌 Project Overview

With the increasing number of cyber threats, traditional rule-based security systems struggle to detect new and complex attacks. This project applies machine learning techniques to analyze network traffic patterns and automatically identify potential intrusions.

The project includes a complete ML pipeline:

- Data preprocessing and cleaning
- Feature analysis and preparation
- Machine learning model training
- Model comparison and evaluation
- Attack classification and performance analysis

---

# 🎯 Objectives

The main objectives of this project are:

- Develop an intelligent intrusion detection system using machine learning.
- Classify network traffic into normal and malicious categories.
- Compare different ML algorithms for cybersecurity applications.
- Evaluate model performance and identify the most effective approach.

---

# 🤖 Machine Learning Models

The following classification algorithms were implemented and evaluated:

| Model | Accuracy |
|------|----------|
| Multi-Layer Perceptron (MLP) | **95%** |
| XGBoost | **94%** |
| Decision Tree | **92%** |
| Naive Bayes | **88%** |
| K-Nearest Neighbors (KNN) | **87%** |

---

# 📊 Results Analysis

The evaluation showed that:

- **MLP achieved the highest performance with 95% accuracy**, demonstrating strong capability in learning complex patterns in network traffic.
- **XGBoost achieved 94% accuracy**, providing highly competitive performance with efficient feature learning.
- **Decision Tree reached 92% accuracy**, offering interpretable attack classification.
- Naive Bayes and KNN achieved lower performance due to limitations in handling complex cybersecurity data patterns.

Overall, neural networks and ensemble learning methods provided the best detection performance.

---

# 🔍 Attack Classes

The model detects the following attack categories:

| Class | Description |
|------|-------------|
| Normal | Legitimate network traffic |
| DoS | Attempts to overload or disrupt network services |
| Probe | Network scanning and information gathering attacks |
| R2L | Unauthorized access from remote machines |
| U2R | Privilege escalation attacks |

---

# 🛠️ Technologies Used

### Programming Language
- Python

### Machine Learning Libraries
- Scikit-learn
- XGBoost
- NumPy
- Pandas
- Matplotlib

### Development Environment
- Jupyter Notebook
- Google Colab

---

# ⚙️ Machine Learning Pipeline

## 1. Data Preprocessing

Performed preprocessing steps including:

- Handling missing values
- Feature selection
- Data normalization
- Encoding categorical features
- Preparing training and testing datasets


## 2. Model Training

Implemented multiple classification algorithms:

- XGBoost Classifier
- Decision Tree Classifier
- KNN Classifier
- Gaussian Naive Bayes
- Multi-Layer Perceptron Neural Network


## 3. Model Evaluation

Models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-score

---

# 👨‍💻 Author

**Omar Tamer Samir**

Computer and Communication Engineering Student  
Zewail City of Science and Technology

# ⭐ Skills Demonstrated

✔ Machine Learning Classification  
✔ Cybersecurity Analytics  
✔ Network Intrusion Detection  
✔ Feature Engineering  
✔ Model Evaluation  
✔ Python Development  
✔ Data Analysis

