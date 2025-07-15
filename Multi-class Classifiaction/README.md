# Rock Paper Scissors Classifier

This is a simple CNN-based image classifier that predicts whether an image is showing a rock, paper, or scissors hand gesture.

---

## Dataset
Used the TensorFlow rock-paper-scissors dataset which already comes with train and test folders. Loaded the images using `image_dataset_from_directory`.

---

## Model Summary
- A basic Convolutional Neural Network (CNN)
- 3 Conv2D layers with MaxPooling
- Flatten → Dense → Softmax
- Trained for 10 epochs using Adam optimizer

---

## What It Does
- Trains the model on labeled images (rock, paper, scissors)
- Evaluates the accuracy on validation data
- Shows predictions on a few sample images

---

## Notes
- This is a small demo project for understanding multiclass classification with images.
- Model performs decently, but not perfect.
- You can try adding data augmentation or use transfer learning if you want to improve it.

---

## Author
Made as part of my learning journey in deep learning.
