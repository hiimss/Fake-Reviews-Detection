# Fake Reviews Detection - BT4012 Project AY 24/25 Semester 1
---
**Dataset** 
We use two dataset for this project, the datasets can be found in these links:
1) https://www.kaggle.com/datasets/mexwell/fake-reviews-dataset
2) https://www.kaggle.com/datasets/naveedhn/yelp-review-with-sentiments-and-features

**Exploratory Data Analysis** 
EDA was conducted to explore, clean, and preprocess the data for model training. Details of this process can be found in the notebook `data_eda_and_preprocessing.ipynb`

**Model Evaluation** 
Multiple machine learning models were implemented and tested for this project:
- Logistic Regression
- Adaboost
- XGBoost
- Random Forest
- PassiveAggressiveClassifier
- ExtraTreesClassifier

After testing and fine-tuning, **PassiveAggressiveClassifier** was chosen as the final model due to its superior recall score of 0.74 after hyperparameter tuning. This model was selected to prioritize minimizing false negatives, a critical factor when identifying fake reviews.
