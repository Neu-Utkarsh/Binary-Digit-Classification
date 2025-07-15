# Decision Tree - Performance Improvement Ideas

Decision Trees can overfit easily, but tuning helps a lot.

## 1. Hyperparameter Tuning
- `max_depth`: Controls depth of tree — tune this to avoid overfitting.
- `min_samples_split` and `min_samples_leaf`: Prevent overly specific branches.
- `max_features`: Use a subset of features for randomness and generalization.

## 2. Preprocessing
- Normalize or scale data — while trees don’t need it, sometimes better spread helps splits.
- Use PCA for noise reduction.

## 3. Ensemble Methods
- Try **Random Forest** or **Gradient Boosting Trees** for better performance.
- Scikit-learn’s `RandomForestClassifier` is a great upgrade path.

## 4. Pruning
- Use `ccp_alpha` (cost-complexity pruning) to simplify overfitted trees.

## 5. Cross-Validation
- Use K-Fold Cross Validation to get stable accuracy metrics.

## 6. Feature Importance
- Plot feature importances to understand how the model is making decisions.
