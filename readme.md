# Cross-Validation of MLPRegressor on the Iris Dataset

This project demonstrates how to evaluate the generalization performance of a neural network model (MLPRegressor) using **20-fold cross-validation** on the classic Iris dataset.

---

## Files

- `mlp_kfold_validation.py` – Contains code for data loading, model training, and evaluation.

---

## Dataset

- **Source:** Scikit-learn's built-in `load_iris()` dataset
- **Features:** 4 numerical measurements per sample
- **Target:** Iris species classification (converted for regression prediction)

---

## What This Project Does

- Loads the Iris dataset and splits it using **KFold cross-validation** with 20 folds.
- Trains a **Multilayer Perceptron Regressor (MLPRegressor)** for each fold.
- Calculates the **Mean Absolute Error (MAE)** for both training and test data in each fold.
- Plots training and testing error across all folds to visualize the model’s consistency and generalization behavior.

---

## Visualizations

Two line plots are generated:

1. **Training Error per Fold**
2. **Testing Error per Fold**

These plots help compare model performance on training vs testing data across different folds.

---

## Concepts Practiced

- Neural network regression using `MLPRegressor`
- Model evaluation using `KFold` cross-validation
- Error analysis using `mean_absolute_error`
- Data visualization using `matplotlib`

---

## How to Run

1. Install required packages:
   ```bash
   pip install scikit-learn matplotlib numpy
    ```
2. Run the script or notebook in your Python environment:
   ```bash
   mlp_kfold_validation.py
    ```