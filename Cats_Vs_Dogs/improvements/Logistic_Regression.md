# Logistic Regression - Performance Improvement Ideas

Logistic Regression is a simple linear model and serves as a baseline. To improve it, consider:

## 1. Feature Engineering
- **Flattened grayscale input loses spatial info** — try resizing to smaller dimensions like 64x64.
- Normalize pixel values between 0 and 1 for better convergence.

## 2. Regularization
- Use L2 Regularization (`penalty='l2'`) to avoid overfitting.
- Tune the regularization strength (`C` parameter) using GridSearchCV.

## 3. Dimensionality Reduction
- Apply PCA to reduce noise and compress features before training.

## 4. Class Balancing
- Check if classes are imbalanced. Use `class_weight='balanced'` in model.

## 5. Data Augmentation
- Since logistic regression doesn’t learn spatial patterns, consider using data augmentation + dimensionality reduction to help indirectly.

## 6. Train-Test Split
- Try different ratios like 80-20 or 70-30 and check generalization.
