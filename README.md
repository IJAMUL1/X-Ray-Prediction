# Classification of Chest X-ray Images for Pneumonia Detection

## Problem
Early detection of pneumonia, especially in children, is crucial for timely treatment and reducing mortality. This project explores the application of various deep learning models for accurately identifying pneumonia in chest X-ray images.

## Dataset
Chest X-ray dataset (Kermany et al. 2018)

## Models Evaluated
- **Basic CNN:** Established a baseline for performance comparison.
- **AlexNet:** Older architecture; provides a historical benchmark.
- **ResNet-18:** Employs residual connections to facilitate deeper training.
- **DenseNet-121:** Promotes feature reuse through dense connectivity.
- **VGG-16:** Utilizes a deep architecture with small convolutional filters.
- **DCGAN:** (Unsuccessful) Explored the potential of a generative adversarial model for discriminative tasks.
- **YOLOv8:** Sophisticated object detector adapted for classification; surprisingly achieved the highest accuracy.

## Key Results
- **YOLOv8** achieved peak accuracy of **93.4%**.
- **ResNet-18** and **DenseNet-121** demonstrated strong performance as architectures well-suited for classification.
- **VGG-16** exhibited the highest average accuracy.

## Considerations
- **Efficiency:** ResNet-18 may be a better choice in resource-constrained environments.
- **Complexity:** YOLOv8's power might be excessive for simple classification tasks.
- **Dataset Imbalance:** Potentially impacts results; requires further investigation.
