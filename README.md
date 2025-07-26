
# Brain Intracranial Hemorrhage Detection and Classification

A machine learning system for detecting and classifying intracranial hemorrhages from CT scans and patient demographics.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Dataset](#dataset)
- [Usage](#usage)
- [Results](#results)
- [Future Scope](#future-scope)

## Project Overview

This research evaluates six machine learning models for hemorrhage detection:
- Logistic Regression
- Random Forest
- SVM
- Gradient Boosting
- XGBoost
- Neural Network

**Key Findings**:
- XGBoost and Neural Networks achieved highest accuracy (>99%)
- Gradient Boosting showed lowest log loss
- Combined imaging + demographic data improved performance

## Key Features

✔ Multi-model comparison framework  
✔ Integrated medical imaging + demographic analysis  
✔ Stratified 5-fold cross-validation  
✔ Comprehensive performance metrics (Accuracy, Log Loss)  
✔ Google Colab compatible implementation  

## Dataset

**Source**: [Kaggle CT Images Dataset](https://www.kaggle.com/datasets/vbookshelf/computed-tomography-ct-images)

**Data Components**:
- `hemorrhage_diagnosis.csv`: Slice-level CT annotations
  - 5 hemorrhage types
  - Fracture indicators
- `patient_demographics.csv`:
  - Age/Gender
  - Clinical notes


## Usage

1. Open in Google Colab

2. Upload dataset files

3. Run all notebook cells

## Results

| Model              | Accuracy | Log Loss |
|--------------------|----------|----------|
| Logistic Regression| 99.28%   | 0.0482   |
| Random Forest      | 100%     | 0.0682   |
| SVM                | 87.29%   | 0.0780   |
| Gradient Boosting  | 100%     | 0.0013   |
| XGBoost            | 99.84%   | 0.0102   |
| Neural Network     | 100%     | 0.0000   |


## Future Scope

- Multi-class hemorrhage type classification
- 3D CT scan analysis
- Clinical deployment optimization
