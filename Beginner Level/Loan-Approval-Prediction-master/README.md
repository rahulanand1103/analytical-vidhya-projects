# Loan-Approval-Prediction
## 1.Business Problem
### 1.1 Description
#### Description
automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.
### Source
https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/

## 2.Machine learning problem
### 2.1 Data
#### 2.1.1 Data Overview

Contain two files 
* <b>train.csv</b>-containing 367 data points</br>
* <b>test.csv</b>-containing 614 data points</br>

Attribute Information:<br>

* 1.<b>Variable</b>-Description<br>
* 2.<b>Loan_ID</b>-Unique Loan ID<br>
* 3.<b>Gender</b>-Male/ Female<br>
* 4.<b>Married</b>-Applicant married (Y/N)<br>
* 5.<b>Dependents</b>-Number of dependents<br>
* 6.<b>Education</b>-Applicant Education (Graduate/ Under Graduate)<br>
* 7.<b>Self_Employed</b>-Self employed (Y/N)<br>
* 8.<b>Applicant Income</b>-Applicant income<br>
* 9.<b>Coapplicant Income</b>-Coapplicant income<br>
* 10.<b>Loan Amount</b>-Loan amount in thousands<br>
* 11.<b>Loan_Amount_Term</b>-Term of loan in months<br>
* 12.<b>Credit_History</b>-credit history meets guidelines<br>
* 13.<b>Property_Area</b>-Urban/ Semi Urban/ Rural<br>
* 14.<b>Loan_Status</b>-Loan approved (Y/N)<br>

### 2.2 Mapping the real-world problem to a Machine Learning Problem
#### 2.2.1 Type of Machine Learning Problem
Loan Will approve or not
#### 2.2.2 Performance metric
* F1-score

## Final Conclusion
* Accuracy on test set: 93.958%
* Precision on test set: 0.933
* Recall on test set: 0.924
* F1-Score on test set: 0.928
