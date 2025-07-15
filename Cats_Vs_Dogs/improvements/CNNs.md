# CNN - Performance Improvement Ideas

CNN already gives strong results, but we can push further.

## 1. More Layers
- Add more Conv2D + MaxPooling2D layers.
- Use Dropout after dense layers to reduce overfitting.

## 2. Data Augmentation
- Use `ImageDataGenerator` or `layers.Random*` for:
  - Horizontal Flip
  - Rotation
  - Zoom
  - Brightness

## 3. Callbacks
- Add `EarlyStopping` to stop training when validation loss plateaus.
- Use `ModelCheckpoint` to save best model based on validation accuracy.

## 4. Learning Rate
- Try using `ReduceLROnPlateau` to decrease learning rate on plateaus.

## 5. Batch Normalization
- Add after Conv2D layers to stabilize and speed up training.

## 6. Transfer Learning
- Use pre-trained models like `MobileNetV2`, `VGG16`, or `ResNet50`.
- Freeze base layers and train only the top layers.

## 7. More Data
- Train on the full 25K image dataset if possible.
- Use cloud resources like Colab Pro for larger training.
