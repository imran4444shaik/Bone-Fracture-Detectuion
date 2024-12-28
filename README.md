# Bone Fracture Detection using EfficientNet and COCO Dataset

This project demonstrates bone fracture detection using transfer learning with EfficientNet. The pipeline includes preprocessing images, training a binary classifier, and evaluating its performance. The dataset used is derived from the COCO annotation format, split into fractured and non-fractured categories.

## Features
- **Dataset Handling**: Loads and preprocesses images and annotations using the COCO dataset format.
- **Mask Visualization**: Generates and visualizes segmentation masks for fractures.
- **Train-Test Split**: Automatically splits the dataset into training, validation, and testing sets.
- **Transfer Learning**: Fine-tunes EfficientNet for binary classification.
- **Model Evaluation**: Provides accuracy metrics for training, validation, and testing phases.



## Prerequisites

Install the following libraries before running the script:

```bash
pip install pycocotools
pip install efficientnet-pytorch
