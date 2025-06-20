# Binary Digit Classifier (0 vs 1)

This project implements a simple neural network from scratch in NumPy to classify handwritten digits '0' and '1' from the scikit-learn digits dataset.

## Highlights
- Implemented forward and backward pass manually (no libraries like TensorFlow/PyTorch)
- Uses Sigmoid activation in all layers
- Visualizes predictions on test images

## Model Performance
 - The model was trained from scratch using a simple 3-layer neural network (manually implemented without using libraries like TensorFlow or PyTorch).

📌 Test Accuracy Achieved: ~51.39%

  - Note:
      This basic model was intentionally built for learning purposes — using only raw pixel data (without feature extraction) and manually computed gradients. The relatively low accuracy is due to:
      Small and shallow neural network.
      Manual training without optimizers or regularization.
      Limited feature learning from raw input.
   - This project was never meant to achieve state-of-the-art performance, but to understand the internals of neural networks and training mechanisms.

## How to Run
1. Open the `.ipynb` file in Jupyter Notebook.
2. Run all cells one-by-one.
3. You'll see:
   - Training logs
   - Final accuracy
   - 16 digit predictions in image format

## Dataset
We use a filtered subset of the sklearn digits dataset containing only digits `0` and `1`.

## Author
Utkarsh Pandey (GitHub: [Neu-Utkarsh](https://github.com/Neu-Utkarsh))
