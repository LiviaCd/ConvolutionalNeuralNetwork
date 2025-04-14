# ConvolutionalNeuralNetwork
**Goal:** Build, train, and evaluate a convolutional neural network (CNN) for image classification, and compare its performance with state-of-the-art pre-trained architectures.

## Methodology
This project focused on designing a convolutional neural network for classifying images into three distinct categories. The main stages included:
Data preprocessing and normalization
Custom CNN architecture design and training
Comparison with advanced pre-trained models (ResNet50, InceptionResNetV2)
Performance evaluation based on classification metrics

## Model Architecture
The custom CNN was built from scratch and included the following components:
Convolutional layers for feature extraction
Batch Normalization to stabilize learning
MaxPooling layers to reduce spatial dimensions
Dropout for regularization
Dense layers for final classification
This baseline model showed good ability to learn and generalize from the training data.

## Comparison with Pre-trained Models
To benchmark the performance, two well-known deep learning architectures were tested:
- **ResNet50** – utilized residual connections to combat vanishing gradients
- **InceptionResNetV2** – combined residual learning with Inception modules for multi-scale feature extraction
Both pre-trained models outperformed the custom CNN in terms of accuracy and generalization, showcasing the advantage of transfer learning and deeper, more optimized architectures.

## Results
The custom CNN achieved solid performance on the image classification task, proving effective for simpler scenarios.
ResNet50 and InceptionResNetV2 achieved higher accuracy, especially on unseen data, due to their depth and architectural optimizations.
Loss and accuracy curves demonstrated smoother training with regularization and better validation performance with transfer learning.

## Conclusion
Building a CNN from scratch offers a valuable learning experience and can yield decent results for small to mid-sized datasets. However, for more demanding tasks, leveraging advanced pre-trained models like ResNet50 or InceptionResNetV2 can dramatically improve performance. The project highlights the importance of architecture design, regularization, and transfer learning in modern deep learning workflows.