# Network Intrusion Detection System (NIDS) using Machine Learning

This project presents a Machine Learning-based Network Intrusion Detection System (NIDS) developed as part of a capstone project using **IBM Watson Studio** and **IBM Cloud Object Storage**. The goal is to classify network traffic into normal activity or various cyber-attack types including **DoS**, **Probe**, **R2L**, and **U2R** using supervised machine learning algorithms.

## 📌 Problem Statement

Develop a robust system to detect network intrusions and distinguish malicious activity from normal network traffic. The system should alert administrators about potential cyber-attacks in real time.

## 📂 Dataset

- **Source:** Kaggle  
- **Link:** [Network Intrusion Detection Dataset](https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection)  
- The dataset contains a wide range of traffic samples including both normal and attack patterns, labeled accordingly.

## 🧠 Machine Learning Approach

- **Best Model:** Snap Decision Tree Classifier
- **Accuracy Achieved:** 99.5%
- **Tools Used:**  
  - IBM Watson Studio (AutoAI)  
  - IBM Cloud Object Storage  
  - Python (scikit-learn, pandas, numpy)  

## ⚙️ System Workflow

1. **Data Collection**: Kaggle dataset used for training and evaluation.
2. **Preprocessing**: Label encoding, normalization, SMOTE for class imbalance.
3. **Model Training**: AutoAI pipeline selection and hyperparameter tuning.
4. **Evaluation**: Accuracy, F1-score, Confusion Matrix, and ROC.
5. **Deployment**: Hosted on IBM Cloud via Watson Studio and Cloud Object Storage.
6. **Interface**: Basic alerting via logs/dashboard (future enhancement).

## 📊 Output

- Highest performing pipeline: **Pipeline 2 – Snap Decision Tree Classifier**
- Cross-validated accuracy: **99.5%**
- Training time: **6 seconds**

## 📦 Technologies Used

- IBM Watson Studio (AutoAI)
- IBM Cloud Lite Tier
- IBM Cloud Object Storage
- Python 3.9+
- Scikit-learn, Pandas, NumPy

## 🚀 Future Improvements

- Integration with real-time traffic streams and dashboards
- Use of Deep Learning models like LSTM/CNN
- Threat response automation using IBM Cloud Functions

## 📜 References

- [Kaggle Dataset](https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection)
- [IBM Watson Studio](https://dataplatform.cloud.ibm.com/docs)
- [Snap ML](https://ibm.github.io/SnapML-doc/)
- [SMOTE Research Paper](https://jair.org/index.php/jair/article/view/10302)

## 👤 Author

**Yojith Reddy**  
Capstone Project – Electronics & Telecommunication Engineering  
IBM Cloud + Machine Learning – Capstone Project  
