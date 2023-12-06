# Introduction

Chronic Kidney Disease (CKD) is a condition in which the kidneys are damaged and cannot filter blood as well as they should. Because of this, excess fluid and waste from blood remain in the body and may cause other health problems, such as heart disease and stroke. CKD has varying levels of seriousness. It usually gets worse over time though treatment has been shown to slow progression. If left untreated, CKD can progress to kidney failure and early cardiovascular disease. When the kidneys stop working, dialysis or kidney transplant is needed for survival. Not all patients with kidney disease progress to kidney failure. To help prevent CKD and lower the risk for kidney failure, control risk factors for CKD, get tested yearly, make lifestyle changes, take medicine as needed, and see your health care team regularly

## CKD by the Numbers

- Kidney diseases are a leading cause of death in the United States
- About 37 million US adults are estimated to have CKD, and most are undiagnosed.
- 40% of people with severely reduced kidney function (not on dialysis) are not aware of having CKD.
- Every 24 hours, 360 people begin dialysis treatment for kidney failure.
- In the United States, diabetes and high blood pressure are the leading causes of kidney failure, accounting for 3 out of 4 new cases.
- In 2019, treating Medicare beneficiaries with CKD cost $87.2 billion, and treating people with ESRD cost an additional $37.3 billion.

## Quick Facts: CKD Snapshot

- Kidney diseases are a leading cause of death in the United States.
- Early CKD has no signs or symptoms.
- Specific blood and urine tests are needed to check for CKD.
- CKD tends to get worse over time.
- CKD can be treated (the earlier treatment starts the better).
- CKD can progress to kidney failure.

_(Source: [Center for Disease Control and Prevention](https://www.cdc.gov/kidneydisease/basics.html))_

# Project Description

The primary goal of this project is to develop robust machine learning models for classifying patients as either at risk or not at risk of chronic kidney disease as CKD is a serious medical condition, and early detection can significantly improve patient outcomes. Two classification algorithms, logistic regression and support vector machine (SVM), were employed to achieve accurate predictions. 

## Dataset

The dataset was obtained from UC Irvine Machine Learning Repository.

- Dataset Size: 400 data points
- Features: 24 variables encompassing a range of medical indicators
- Class: Binary classification indicating the presence or absence of chronic kidney disease

## Repository Structure

kidney.csv: Contains the raw data downloaded from the data source.
01_datasets.xlsx: Pre-processed and feature reduced data.
Chronic_Kidney_Disease.ipynb: Jupyter notebooks detailing the entire data exploration, preprocessing, and model development process.
