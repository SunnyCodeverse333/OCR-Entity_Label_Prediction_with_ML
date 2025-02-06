# OCR-Entity_Label_Prediction_with_ML
This project utilizes machine learning models (Neural Networks, Decision Trees, XGBoost, and Random Forest) to predict entitiy from OCR-extracted data.
# Entity Extraction and Prediction from OCR Data

## Overview

This project aims to extract and predict entities from OCR-processed tax-related documents using machine learning models. The dataset consists of token-level extractions from OCR images, which include information such as token positions, coordinates, and the corresponding transcript data. The main goal of this project was to predict the "field" (entity) column given other input columns, using machine learning algorithms.

## Dataset

The dataset contains two parts:
1. **Training Data**: Includes start and end indices, token coordinates (top-left and bottom-right), the transcript (OCR text), and the ground truth label (field).
2. **Testing Data**: Includes start and end indices, token coordinates, and the transcript, but no labels. The task was to predict these labels using machine learning models.

## Tasks Performed

1. **Data Preprocessing and Exploration**:
   - Cleaned and filtered the provided dataset.
   - Performed exploratory data analysis (EDA) to understand the structure and distribution of the data.

2. **Modeling**:
   - Trained multiple machine learning models, including:
     - Neural Networks
     - Decision Trees
     - XGBoost
     - Random Forest
   - Used these models to predict the *'field' (entity)* given other input entities

3. **Evaluation**:
  
   - Analyzed model performance to ensure high prediction accuracy.


- Models and tools used: Scikit-learn, XGBoost, TensorFlow, and other Python libraries.
