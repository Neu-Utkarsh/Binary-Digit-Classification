# Cats vs Dogs - Binary Image Classification

This project classifies images of cats and dogs using three models:
- Logistic Regression (with flattened pixel values)
- Decision Tree
- Convolutional Neural Network (CNN)

We compare performance using accuracy, precision, recall, and F1-score.

## 📁 Dataset
- Dataset Source: [Kaggle - Cat vs Dog](https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset)

- Preprocessed into:
  - `train/` with cats and dogs folders
  - `test/` with unseen images for evaluation

## 🧠 Models Used

### 1. Logistic Regression
- Input: Flattened 2D images into 1D vectors
- Performance: Baseline model

### 2. Decision Tree
- Input: Same as logistic regression
- Captures more complex decision rules

### 3. CNN (Convolutional Neural Network)
- Input: 2D image tensors with channels
- Layers: Conv2D, MaxPooling2D, Dense
- Performance: Best among the three

## 📊 Evaluation
All models are evaluated using:
- Accuracy
- Classification Report (Precision, Recall, F1-score)
- Bar plots comparing macro-average metrics

## 📂 Folders
- `improvements/`: Contains detailed suggestions on how to improve each model further.

## 📝 Notes

- For model **comparison (Logistic Regression vs Decision Tree vs CNN)**, only **2,000 images** were used (1,000 cats + 1,000 dogs) for faster prototyping.
- For the **final CNN model**, the full **25,000-image dataset** was used (from Kaggle).
