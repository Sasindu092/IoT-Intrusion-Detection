# AI-Based Intrusion Detection System for IoT/IIoT (Ongoing)

## 📌 Project Overview
This project focuses on the design and implementation of an AI-based learning model for an **Intrusion Detection System (IDS)**. The goal is to protect complex environments including **Cloud Computing**, **Blockchain Networks**, and **IoT/IIoT Perception layers** from evolving cyber threats.

The system is engineered to pre-process and analyze data from digital sensors to identify security breaches across various connectivity protocols.



## 📊 Dataset: Edge-IIoTset
The project utilizes the **Edge-IIoTset**. This dataset contains fourteen specific attacks classified into five major threat categories:
* **DoS/DDoS attacks**
* **Information gathering**
* **Man-in-the-middle (MITM) attacks**
* **Injection attacks**
* **Malware attacks**

## 🛠️ Technical Implementation
As per the software requirements, the implementation is **Python-based** and covers:
* **Machine Learning/Deep Learning:** Deployment of a predictive classifier to provide threat intelligence.
* **Data Splitting:** Utilization of a **Training set** for model learning and validation, and a **Testing set** for final evaluation.
* **Performance Metrics:** Analysis using Confusion Matrices and ROC curves.



## 🚀 Project Structure
Following the academic report structure, the repository is organized to support:
1. **Data Preprocessing:** Handling sensor data and connectivity protocols.
2. **Methodology:** Selection and architecture of ML/DL algorithms.
3. **Comparative Analysis:** Performance evaluation against alternative models.

## 📖 How to Use
1. **Clone the Repo:** `git clone https://github.com/YourUsername/IoT-Intrusion-Detection.git`
2. **Install Requirements:** `pip install pandas numpy scikit-learn matplotlib`
3. **Data Setup:** Place the `Edge-IIoTset.csv` in the root folder (Note: This file is ignored by Git due to size).
4. **Run Notebook:** Execute the cells in `Assignment.ipynb`.

---
*Developed for **EE3354: Machine Learning**.*
