---
date: '3'
title: 'Credit Card Fraud Detection'
cover: './demo.png'
github: 'https://github.com/enkhoyun218/card-fraud-detection'
tech:
  - Python
  - scikit-learn
  - imbalanced-learn
  - pandas
---

A fraud model built on 284K credit card transactions where only 0.17% are fraud, so accuracy is meaningless and the real work is recall and precision. I compared five models by PR-AUC (0.86 for the best), saw that class weights and SMOTE on a linear model caught more fraud while flooding the results with false alarms, and then tuned the random forest's threshold to catch 85% of fraud at 83% precision.
