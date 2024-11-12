# Papyrus: Handwritten Digit Classification with CNN
**Papyrus** is a deep learning project that leverages a Convolutional Neural Network (CNN) to classify handwritten digits. It is trained using the MNIST dataset.
The model is designed with TensorFlow and Keras, achieving strong performance in recognizing digits from 0 to 9, which makes it suitable for digit recognition tasks and educational purposes.

## Model Architecture
The model architecture consists of the following layers:
1. **Feature Extraction Layers:**
   - Two `Conv2D` layers with 32 filters and ReLU activation to extract spatial features from the input images.
   - Two additional `Conv2D` layers with 64 filters to extract more complex features from the image.

2. **Regularization Layers:**
   - `MaxPooling2D` layers after each block of convolutions to reduce the spatial dimensions.
   - `BatchNormalization` layers to stabilize and speed up the training process.
   - `Dropout` layers (0.25 after the first block and 0.5 before the final classification layer) to prevent overfitting.

3. **Flattening Layer:**
   - The `Flatten` layer reshapes the pooled feature maps into a 1D vector before passing them to the fully connected layers.

4. **Classification Layers:**
   - A dense layer with 256 neurons and ReLU activation to capture class-specific patterns.
   - A final dense layer with softmax activation for classification, outputting probabilities for each class.

## Results
After training, the model achieves approximately 99% accuracy on the test set, making it a reliable model for handwritten digit recognition.
