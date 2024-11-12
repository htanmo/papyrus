# Papyrus: Handwritten Digit Classification with CNN
**Papyrus** is a deep learning project that leverages a Convolutional Neural Network (CNN) to classify handwritten digits. It is trained using the MNIST dataset.
The model is designed with TensorFlow and Keras, achieving strong performance in recognizing digits from 0 to 9, which makes it suitable for digit recognition tasks and educational purposes.

## Model Architecture
The model architecture consists of the following layers:
- **Feature Extraction Layers:** Two convolutional layers to extract key spatial features from the input images.
- **Regularization Layers:** Max-pooling layers to downsample feature maps and reduce dimensionality, paired with dropout layers to mitigate overfitting.
- **Flattening Layer:** A flatten layer to reshape the pooled feature maps into a single vector, preparing them for the fully connected layers.
- **Classification Layers:** Two fully connected (dense) layers to learn class-specific patterns and output probabilities. A dropout layer between these dense layers provides additional regularization.

## Results
After training, the model achieves approximately 99% accuracy on the test set, making it a reliable model for handwritten digit recognition.
