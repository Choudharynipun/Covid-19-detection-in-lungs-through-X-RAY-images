## Chest X-ray Classification Model

### Overview:
This repository contains a Convolutional Neural Network (CNN) model for binary classification of chest X-ray images into 'covid' and 'normal' classes. The model is built using the Keras deep learning framework and trained on a dataset comprising chest X-ray images.

### Model Architecture:
- Input images: RGB images with a size of (150, 150) pixels.
- Convolutional layers: Multiple convolutional layers with increasing filter sizes and max pooling for feature extraction.
- Dense layers: Fully connected layers with ReLU activation for capturing complex patterns.
- Output layer: A single neuron with a sigmoid activation for binary classification ('covid' or 'normal').

### Training:
- The model is trained using the RMSprop optimizer and binary cross-entropy loss.
- Data augmentation techniques, including rescaling, shearing, zooming, and horizontal flipping, are applied to enhance generalization.

### Usage:
1. Clone the repository.
2. Install the required dependencies (Keras, TensorFlow, etc.).
3. Run the provided script to train and evaluate the model on your own dataset.

Feel free to use, modify, and contribute to this project. If you find it helpful, kindly give credit by linking back to this repository. Happy coding!

---
