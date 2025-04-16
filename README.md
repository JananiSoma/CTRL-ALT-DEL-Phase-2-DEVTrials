# CTRL-ALT-DEL-Phase-2-DEVTrials
Kubernetes Issue Prediction using Machine Learning

📌 Project Overview

This project aims to develop a machine learning model that can predict potential issues in Kubernetes clusters using given or simulated data. By leveraging Random Forest Classifier, SMOTE Analysis, K-Means Clustering, and One-Class SVM, the model identifies patterns and anomalies in Kubernetes performance metrics.

📂 Repository Contents • Untitled1.ipynb - Jupyter Notebook containing data analysis, feature selection, and model training steps. • k8s_data.csv - Dataset containing Kubernetes cluster performance metrics and labels. • CTRL + ALT + DEL (Phase 1).pptx - Presentation explaining the project workflow, methodology, and results.

🚀 Features • Exploratory Data Analysis (EDA) • Data cleaning and preprocessing • Correlation heatmaps for feature selection • Machine Learning Models • Random Forest Classifier for multi-class classification • SMOTE (Synthetic Minority Over-sampling Technique) to handle class imbalance • K-Means Clustering for unsupervised anomaly detection • One-Class SVM for outlier detection

📊 Results • Generated a correlation heatmap to visualize feature relationships. • Improved model accuracy using SMOTE for balanced class distribution. • Clustered data using K-Means to identify potential failure patterns. • Detected anomalies using One-Class SVM for early issue prediction.

🔮 Future Work • Enhancing feature selection using advanced statistical techniques. • Deploying the model into a live Kubernetes cluster for real-time monitoring. • Integrating alerting mechanisms for proactive issue resolution.

🤝 Contributing

We welcome contributions! Feel free to fork the repo, create a new branch, and submit a pull request.

📜 License

This project is licensed under the MIT License.
