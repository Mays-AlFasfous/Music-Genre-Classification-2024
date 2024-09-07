# Music Genre Classification 🎵
### Team Project
This repository contains the code and documentation for a music genre classification project. Our team worked collaboratively to analyze audio data, apply machine learning techniques, and build predictive models that classify songs into different genres based on their audio features.

---

## Project Overview
Music classification plays a pivotal role in various applications, from music streaming platforms to audio analytics. This project aims to classify songs into their respective genres by leveraging the power of machine learning. Using a diverse dataset of audio features, we designed and trained models to predict music genres with high accuracy.

---

## Dataset
We used a dataset consisting of 14,396 entries and 18 columns, including various audio-related features such as tempo, loudness, key, instrumentalness, and more. The dataset also contained missing values that required handling during the data preprocessing phase.

**Key points**:
- Features: Tempo, Loudness, Danceability, Key, Instrumentalness, etc.
- Missing Values: Handled missing values in 'Popularity', 'Key', and 'Instrumentalness'.

---

## Project Structure
- **Data Preprocessing**: Data cleaning, handling missing values, and feature selection.
- **Feature Engineering**: Generated new features and dropped irrelevant ones.
- **Modeling**: Built and tested multiple models, including ensemble methods like stacking and voting classifiers.
- **Evaluation**: Evaluated models using performance metrics like F1 Score and Cross-Validation.

---

## Models Used
Our team explored various machine learning models, focusing primarily on ensemble methods to improve the classification performance:

1- **Stacking Model**:
- Base models: CatBoost, XGBoost, LightGBM, RandomForest.
- Final Estimator: Logistic Regression.

2- **Other Models**:
CatBoostClassifier, XGBClassifier, RandomForestClassifier.

---

## Results and Findings
- Best Model: The stacking model with Logistic Regression as the final estimator achieved the highest F1 score among all tested models.
- Hyperparameter Tuning: After experimenting with GridSearchCV, we found that tuning didn’t significantly improve performance, so we opted to skip it in the final implementation.

---

## Installation and Usage 🛠️
### Requirements:
- Python 3.x
- Required Libraries:
  - ```pandas```
  - ```numpy```
  - ```scikit-learn```
  - ```xgboost```
  - ```catboost```
  - ```lightgbm```
  - ```matplotlib```
  - ```seaborn```

Install dependencies:
```bash
pip install -r requirements.txt
```
---

## Usage:
Run the main notebook or script to train the models and evaluate performance:
```bash
python MusicGenreClassification2024_G3.ipynb
```
The notebook also provides visualizations and detailed steps for data processing and model training.

---

## Contributors
- **Mays Al-Fasfous**
- **Hesham Alsaadi**
- **Sedra Merkhan**
- **Ahmad Sadik**

This project was developed as part of a team collaboration to tackle the Kaggle competition on music genre classification. All team members contributed to various aspects of the project, including data preprocessing, feature engineering, and modeling.
