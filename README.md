# **<p align="center">Credit Risk Analysis</p>**

### **<p align="center">A Machine Learning analytics report designed to predict credit risk.</p>**

---
## Overview
This report is designed to determine the Credit Card Risk of individuals based on a dataset provided by LendingClub. The data is unbalanced considering the fact that most applicants are considered low-risk (<1%). In order to account for this and provide the best Machine Learning algorithym we have tested over, under and combinatory sampling. The results of our analysis are below, followed by a summary and our suggested model to adopt for this problem.

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

1. **Roles that need to be filled:** Within the next five years, there will be an employee deficit of 90,398 individuals.
   - It is recommended that Pewlett Hackard aim to hire 18,080 employees each year for the following five years to accommodate these changes.
2. **Mentorship Deficit:** As seen in the table below, there is a significant deficit in the number of available mentors vs the number of retirees (and requisite new hires) in every department.
    - Additional parameters (I.E. employees born from 1965-1968) for qualified mentors should be considered to bridge these gaps.

<p align="center">
   <img width="800" height="400" src="https://github.com/Jamesrx33/Pewlett-Hackard-Analysis/blob/main/Visuals/Retirement_vs_Mentors.png?raw=true">
</p>

3. **Suggested Additional Analysis:** Replacements need to be found for the two retiring department managers. The following querys will compile a list of current employees, their title and department. These can be used to select a replacement manager for the departments losing one.

<p align="center">
   <img width="800" height="800" src="https://github.com/Jamesrx33/Pewlett-Hackard-Analysis/blob/main/Visuals/Query%20Suggestions.png?raw=true">
</p>


---

## Reference Documentation - [Source Code Repository](https://github.com/Jamesrx33/Pewlett-Hackard-Analysis), [Download .zip file](https://github.com/Jamesrx33/Pewlett-Hackard-Analysis/archive/refs/heads/main.zip)
