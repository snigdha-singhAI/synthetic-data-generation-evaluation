# Synthetic Data Generation and Evaluation Using Machine Learning

## Overview

This project explores whether machine learning models trained on synthetic healthcare data can achieve performance comparable to models trained on real patient records.

Using the Pima Indians Diabetes Dataset, synthetic patient records were generated using Gaussian statistical sampling and evaluated using machine learning classification models.

The project demonstrates the potential of privacy-preserving AI by generating statistically similar healthcare records without exposing real patient information.

## Team Members

* Snigdha Singh
* Shubhayu Bhattacharya
* Shaury Tandon
* Sohan Saha

## My Contributions

* Data preprocessing and cleaning
* Missing value handling and imputation
* Exploratory Data Analysis (EDA)
* Synthetic data generation
* Machine learning model training and evaluation
* Visualization and interpretation of results
* Research documentation and report writing

## Dataset

Pima Indians Diabetes Dataset

* 768 patient records
* 8 clinical features
* Binary diabetes outcome

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Methodology

1. Data Acquisition
2. Missing Data Handling
3. Outlier Detection
4. Univariate Analysis
5. Bivariate Analysis
6. Label Encoding
7. Synthetic Data Generation
8. Machine Learning Evaluation

## Machine Learning Models

* Logistic Regression
* Random Forest

## Results

| Model               | Real Data | Synthetic Data |
| ------------------- | --------- | -------------- |
| Logistic Regression | 69.48%    | 70.13%         |
| Random Forest       | 77.92%    | 67.53%         |

## Key Findings

* Logistic Regression performed almost identically on synthetic and real data.
* Synthetic data preserved important statistical patterns.
* Random Forest performance decreased due to loss of complex feature interactions.
* Synthetic healthcare data shows promise for privacy-preserving machine learning applications.

## Repository Contents

* synthetic_data_generation.ipynb
* Synthetic_Data_Generation_Report.docx
* Synthetic_Data_Generation_Presentation.pptx

## Future Work

* CTGAN-based synthetic data generation
* Diffusion models for tabular data
* Statistical similarity metrics
* Advanced privacy evaluation methods
