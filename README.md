# AI-Based Intrusion Detection System for IoT/IIoT (Ongoing)

AI-Based Intrusion Detection System for IoT/IIoT

📌 Project Overview

This project focuses on the design and implementation of an AI-based Intrusion Detection System (IDS). The goal is to protect complex environments including Cloud Computing, Blockchain Networks, and IoT/IIoT Perception layers from evolving cyber threats.

📊 Dataset: Edge-IIoTset

The system utilizes the Edge-IIoTset, a comprehensive library of IoT/IIoT connectivity protocols. The model classifies traffic into 15 categories (1 Normal + 14 Attack types) across five major threat categories:

1. DoS/DDoS attacks
2. Information gathering
3. Man-in-the-middle (MITM) attacks
4. Injection attacks
5. Malware attacks

🛠️ Completed Technical Implementation

I have moved beyond a single classifier to a full Comparative Analysis of 4 different algorithms:

🛠️ Data Preprocessing & Engineering:

Handled high-dimensional network telemetry data.

Advanced Cleaning: Resolved float32 overflow and infinity errors inherent in the Edge-IIoTset by implementing data clipping and numeric coercion.

Multi-Model Deployment: Implemented and evaluated 4 distinct machine learning architectures:

Ensemble Methods: Random Forest, XGBoost.

Distance & Boundary Based: K-Nearest Neighbors (KNN).

Tree-Based: Decision Trees.

🛠️ Performance Evaluation:

Generated Confusion Matrices for every algorithm to analyze class-specific sensitivity.

Calculated Accuracy, Precision, Recall, and F1-Scores.

Created a Comparative Performance Summary to identify the most efficient model for real-time Edge deployment.


Developed for EE3354: Machine Learning.