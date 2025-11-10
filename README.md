# Titanic Survival Prediction

This project predicts whether a passenger survived the Titanic disaster using classic machine learning models.  
It demonstrates a complete ML workflow — data preprocessing, feature encoding, model training, and evaluation.

## Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)

## Results (Example)
| Model | Accuracy |
|--------|-----------|
| Logistic Regression | 0.80 |
| Decision Tree | 0.81 |
| Random Forest | 0.84 |
| KNN | 0.78 |

The Random Forest Classifier performed best overall.

## Dataset
Kaggle: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.  
2. Run all cells in order.  
3. Ensure you have the following libraries installed:
pandas
numpy
matplotlib
scikit-learn


To install dependencies:
```bash
pip install -r requirements.txt

## Visualization

A comparison bar chart was used to visualize accuracy scores across different models.

---

## Future Improvements

* Add hyperparameter tuning using GridSearchCV.
* Use feature importance analysis for interpretability.
* Explore deep learning models like simple neural networks.
* Deploy the model as a small web app (e.g., Streamlit).

---

Author: Rakshan G. K.
Date: November 2025

