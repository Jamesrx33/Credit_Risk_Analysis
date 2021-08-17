# **<p align="center">Credit Risk Analysis</p>**

### **<p align="center">A Machine Learning analytics report designed to predict credit risk.</p>**

---
## Overview
This report is designed to determine the Credit Card Risk of individuals based on a dataset provided by LendingClub. The data is unbalanced considering the fact that most applicants are considered low-risk (<1% high_risk). In order to account for this and provide the best Machine Learning algorithym we have tested over, under and combinatory sampling. The results of our analysis are below, followed by a summary and our suggested model to adopt for this problem.

---
## **<p align="center">Results - RandomOverSampler</p>**
---

**Balanced Accuracy Score**
<p align="center">
   <img width="700" height="250" src="https://github.com/Jamesrx33/Credit_Risk_Analysis/blob/main/Resources/Images/ROS_Accuracy.png?raw=true">
</p>

**Imbalanced Classification Report**

<p align="center">
   <img width="700" height="250" src="https://github.com/Jamesrx33/Credit_Risk_Analysis/blob/main/Resources/Images/ROC_Table.png?raw=true">
</p>

1. **Balanced Accuracy Score:** The balanced accuracy score of the RandomOverSampling model was 0.65
2. **Precision:** The precision was .01 and 1.0 for High and Low risk respectively
3. **Recall:** The recall was .69 and .60 for High and Low risk respectively

---
## **<p align="center">Results - SMOTE</p>**
---

**Balanced Accuracy Score**
<p align="center">
   <img width="700" height="250"src="https://github.com/Jamesrx33/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTE_Accuracy.png?raw=true">
</p>

**Imbalanced Classification Report**

<p align="center">
   <img width="700" height="250" src="https://github.com/Jamesrx33/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTE_Table.png?raw=true">
</p>

1. **Balanced Accuracy Score:** The balanced accuracy score of the SMOTE model was 0.66
2. **Precision:** The precision was .01 and 1.0 for High and Low risk respectively
3. **Recall:** The recall was .63 and .69 for High and Low risk respectively

---
## **<p align="center">Results - ClusterCentroids</p>**
---

**Balanced Accuracy Score**
<p align="center">
   <img width="700" height="250" src="https://github.com/Jamesrx33/Credit_Risk_Analysis/blob/main/Resources/Images/CC_Accuracy.png?raw=true">
</p>

**Imbalanced Classification Report**

<p align="center">
   <img width="700" height="250" src="https://github.com/Jamesrx33/Credit_Risk_Analysis/blob/main/Resources/Images/CC_Table.png?raw=true">
</p>

1. **Balanced Accuracy Score:** The balanced accuracy score of the ClusterCentroids model was 0.54
2. **Precision:** The precision was .01 and 1.0 for High and Low risk respectively
3. **Recall:** The recall was .69 and .40 for High and Low risk respectively
---
## **<p align="center">Results - SMOTEENN</p>**
---

**Balanced Accuracy Score**
<p align="center">
   <img width="700" height="250"src="https://github.com/Jamesrx33/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTEENN_Accuracy.png?raw=true">
</p>

**Imbalanced Classification Report**

<p align="center">
   <img width="700" height="250"src="https://github.com/Jamesrx33/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTEENN_Table.png?raw=true">
</p>

1. **Balanced Accuracy Score:** The balanced accuracy score of the SMOTEENN model was 0.66
2. **Precision:** The precision was .01 and 1.0 for High and Low risk respectively
3. **Recall:** The recall was .75 and .58 for High and Low risk respectively
---
## **<p align="center">Results - BalancedRandomForestClassifier</p>**
---

**Balanced Accuracy Score**
<p align="center">
   <img width="700" height="250" src="https://github.com/Jamesrx33/Credit_Risk_Analysis/blob/main/Resources/Images/BRFC_Accuracy.png?raw=true">
</p>

**Imbalanced Classification Report**

<p align="center">
   <img width="700" height="250" src="https://github.com/Jamesrx33/Credit_Risk_Analysis/blob/main/Resources/Images/BRFC_Table.png?raw=true">
</p>

1. **Balanced Accuracy Score:** The balanced accuracy score of the BalancedRandomForestClassifier model was 0.79
2. **Precision:** The precision was .03 and 1.0 for High and Low risk respectively
3. **Recall:** The recall was .70 and .87 for High and Low risk respectively
---
## **<p align="center">Results - EasyEnsembleClassifier</p>**
---

**Balanced Accuracy Score**
<p align="center">
   <img width="700" height="250" src="https://github.com/Jamesrx33/Credit_Risk_Analysis/blob/main/Resources/Images/EEC_Accuracy.png?raw=true">
</p>

**Imbalanced Classification Report**

<p align="center">
   <img width="700" height="250" src="https://github.com/Jamesrx33/Credit_Risk_Analysis/blob/main/Resources/Images/EEC_Table.png?raw=true">
</p>

1. **Balanced Accuracy Score:** The balanced accuracy score of the EasyEnsembleClassifier model was 0.92
2. **Precision:** The precision was .05 and 1.0 for High and Low risk respectively
3. **Recall:** The recall was .93 and .90 for High and Low risk respectively
---
## Summary
---

In all of our models, the level of precision in reference to High Risk applicants was very poor. We did see a marked imporvement in recall, however, when the Ensemble models were applied to our data. When considering a Credit Card application, Precision would be more important than recall because we want to correctly identify all High Risk applicants. All of our models have a precision of .03 or less in regards to High Risk applicants. Considering this, we are of the opinion that none of these models would be advantageous to use when trying to predict credit risk in an applicant. 

---

## Reference Documentation - [Source Code Repository](https://github.com/Jamesrx33/Credit_Risk_Analysis), [Download .zip file](https://github.com/Jamesrx33/Credit_Risk_Analysis/archive/refs/heads/main.zip)
