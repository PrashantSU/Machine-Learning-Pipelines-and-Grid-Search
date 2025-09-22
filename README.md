# Machine Learning Pipelines and Grid Search for Fetal Health Classification

This repository contains a complete workflow for **Fetal Health Classification** using machine learning pipelines, ensemble methods, and hyperparameter tuning. The project demonstrates how to preprocess data, handle imbalanced datasets, and select the best model using Grid Search and Randomized Search.

## Dataset
The project uses the [Fetal Health Classification dataset](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification) from Kaggle.  
- **Records:** 2126  
- **Classes:**  
  - Normal: 1  
  - Suspect: 2  
  - Pathological: 3  

## Features
- Data preprocessing: StandardScaler, MinMaxScaler, handling duplicates  
- Handling imbalanced data: RandomOverSampler, SMOTE, ADASYN  
- Ensemble methods: VotingClassifier, Bagging, Random Forest, AdaBoost, XGBoost  
- Hyperparameter tuning: Grid Search and Randomized Search  
- Custom pipeline with `SquaredFeatureTransformer`  
- Nested k-fold cross-validation for robust model evaluation  

## Results
- XGBoost and Random Forest performed best for this dataset  
- Pipeline integration simplified preprocessing, resampling, and model training  
- Nested CV achieved high accuracy (~94–96%)  

## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/fetal-health-ml.git
    ```
2. Open `Machine Learning Pipelines and Grid Search.ipynb` in Google Colab or Jupyter Notebook.  
3. Run the notebook cells step by step to reproduce the results.  

## References
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/)  
- [Imbalanced-learn Documentation](https://imbalanced-learn.org/)  
- [XGBoost Documentation](https://xgboost.readthedocs.io/)  

---

📌 **Author:** Your Name  
📌 **Date:** 2025-09-22
