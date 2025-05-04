
CNN Image Classification – CIFAR-10

Objective:
Implement and evaluate a basic Convolutional Neural Network (CNN) for image classification using the CIFAR-10 dataset.

Tools & Libraries:
Python, TensorFlow/Keras, NumPy, Matplotlib, Scikit-learn

Dataset:
CIFAR-10: 60,000 32x32 color images in 10 classes

Task 1: Data Exploration

Displayed 5 sample images with labels

Checked data shapes and label distribution

Normalized images and split data (80/20)

Task 2: CNN Model

Conv2D → ReLU → MaxPooling → Dropout (×2)

Flatten → Dense → Output (Softmax)

Compiled with categorical_crossentropy and Adam optimizer

Trained for 15 epochs

Plotted training and validation accuracy and loss

Task 3: Evaluation

Evaluated accuracy on test set

Generated confusion matrix and classification report

Showed examples of correct and incorrect predictions

Task 4: Improvements

Tested with SGD and RMSProp optimizers

Compared performance with baseline
