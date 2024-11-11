# Papyrus: Handwritten Digit Classification with CNN
**Papyrus** is a deep learning project that leverages a Convolutional Neural Network (CNN) to classify handwritten digits. It is trained using the MNIST dataset.
The model is designed with TensorFlow and Keras, achieving strong performance in recognizing digits from 0 to 9, which makes it suitable for digit recognition tasks and educational purposes.

## Model Architecture
The Model has the following layers:
- Two convolutional layers for feature extraction
- Max-pooling and dropout layers to prevent overfitting
- A flatten layer
- Two fully connected layer to learn and output class probabilities with a dropout layer between them. 

## Results
After training, the model achieves approximately 99% accuracy on the test set, making it a reliable model for handwritten digit recognition.
