# Credit Card Fraud Detection
The challenge here was to recognize fraudulent credit card transactions so as to avoid the credit card holders being charged for items they did not purchase.

Main challenge that was involved in credit card fraud detection was that the data-set available was highly biased i.e most of the transactions (99.8%) are not fraudulent. This makes it hard for detecting the fraudulent ones. This could lead to misclassified data which could be an another major issue, as not every fraudulent transaction is caught and reported.

My attempt on this problem was to resample the data using the following algorithms:
1. Random Up-Sampling
2. Random Down-Sampling
3. SMOTE
4. Near-Miss

The following classification algorithms were tested on the data:
1. Logistic Regression
2. KNN
3. Random Forest
4. XGBoost
