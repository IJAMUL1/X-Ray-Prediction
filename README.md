Project Title: Classification of Chest X-ray Images for Pneumonia Detection

Problem:  Early detection of pneumonia, especially in children, is crucial for timely treatment and reducing mortality. This project explores various deep learning models to identify pneumonia in chest X-ray images.

Dataset: Chest X-ray dataset (Kermany et al. 2018)

Models Evaluated:

Basic CNN: Established a baseline performance.
AlexNet: Older architecture, serves as a comparison point.
ResNet-18: Leverages residual connections for deeper training.
DenseNet-121: Dense connectivity promotes feature reuse.
VGG-16: Deep architecture with small convolutional filters.
DCGAN: (Unsuccessful) Explored discriminative capabilities of a generative model.
YOLOv8: Sophisticated object detector; adapted for classification.
Results:

YOLOv8 achieved the highest accuracy of 93.4%. Surprisingly effective despite its primary object detection design.
ResNet-18 and DenseNet-121 showed strong performance as good choices tailored for classification.
VGG-16 demonstrated the highest average accuracy.
Key Considerations:

Efficiency: ResNet-18 may be preferred for resource-constrained settings.
Complexity: YOLOv8, while powerful, might be overkill for simple classification.
Dataset Imbalance: Could impact results - not explicitly addressed in this study
