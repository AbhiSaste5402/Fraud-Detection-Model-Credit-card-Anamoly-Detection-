# Fraud-Detection-Model-Credit-card-Anamoly-Detection-

This project involves the detection of credit card fraud using anomaly detection techniques. The dataset used in this project contains credit card transactions made by European cardholders in September 2013, and comprises 284,807 transactions, out of which only 492 are fraudulent, resulting in a highly imbalanced dataset where the positive class (frauds) account for 0.172% of all transactions.

The input features of the dataset are numerical and have been obtained through a Principal Component Analysis (PCA) transformation. The transformed features are labeled as V1, V2, ..., V28, while the remaining features that have not undergone PCA transformation are Time and Amount. The Time feature captures the time elapsed in seconds between each transaction and the first transaction in the dataset, while the Amount feature represents the monetary amount involved in each transaction.

The primary objective of this project is to detect fraudulent transactions in the dataset using different anomaly detection techniques and comparing their performance. Three different techniques have been used for this purpose: Isolation Forest, Local Outlier Factor (LOF), and Support Vector Machines (SVM). 

The results of the project show that the Isolation Forest algorithm outperforms the other two algorithms in terms of accuracy, precision, and recall. Specifically, the Isolation Forest algorithm detected 73 errors, which is less than the 97 errors detected by the LOF algorithm and significantly less than the 8516 errors detected by the SVM algorithm. Furthermore, the Isolation Forest algorithm achieved an accuracy rate of 99.74%, which is higher than the LOF accuracy rate of 99.65% and much higher than the SVM accuracy rate of 70.09%. 

When evaluating the detection rate of fraud cases, the Isolation Forest algorithm performed significantly better than the LOF algorithm, with a detection rate of 27% compared to LOF's detection rate of only 2%. The SVM algorithm was unable to detect any fraudulent transactions. 

Overall, this project demonstrates the effectiveness of the Isolation Forest algorithm for detecting fraudulent credit card transactions. The results suggest that increasing the sample size or using deep learning algorithms could improve the accuracy further, but at the cost of increased computational expense. Furthermore, the use of complex anomaly detection models could potentially enhance the accuracy of fraud detection even further.
