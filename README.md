# Convolutional Neural Networks (CNN)

## What are CNNs?
- Neural Networks are a supervised learning technique that vaguely mimics the human brain. 
- Convolutional Neural Networks (CNN) are a type of Neural Network with various applications in computer vision, such as taking in a picture and identifying what the picture is of.
 
## How to Improve Model Performance
- Adjust the number of epochs to be right before the testing accuracy starts to dip so you can maximize accuracy and prevent overfitting
  - **epochs**: number of times the model will see the entire training dataset
  - **overfitting**: when the model finds random, unrelated connections in the training data and learns them
- Adjust the batch size to maximize accuracy 
  - **batch size**: how many images get sent to the model at a time when training

## Tech Roulette Week 6
- Learned about CNNs and CNN architecture (e.g. convolution layers, pooling layers, fully connected layers, dropout layers)
- Built a CNN using the MNIST ("Modified National Institute of Standards and Technology") dataset, which contains thousands of handwritten images of single digits from 0 to 9
