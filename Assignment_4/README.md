# Deep Learning Practical 4  
## Imbalanced Image Classification, Model Comparison & Feature Visualization

## Overview
This assignment focuses on handling class imbalance in image classification tasks, comparing multiple CNN architectures, evaluating performance using advanced metrics, and analyzing learned feature representations.

Two datasets are used:
- Imbalanced CIFAR-10 (artificial long-tailed distribution)
- Flowers Dataset (ImageFolder format)

The project also includes transfer learning experiments and model explainability using Grad-CAM.

---

## Objectives

- Handle class imbalance using sampling and loss-based techniques
- Compare at least two CNN architectures
- Evaluate models using advanced performance metrics
- Analyze model complexity (parameters, FLOPs, inference time)
- Visualize learned features (PCA, t-SNE, UMAP)
- Apply transfer learning across datasets
- Use Grad-CAM for model explainability

---

## Datasets Used

### 1. Imbalanced CIFAR-10
- Created using a long-tailed class distribution
- Used to test imbalance handling techniques

### 2. Flowers Dataset
- Multi-class real-world image dataset
- Used for transfer learning and visualization

---

## Models Implemented

- ResNet18
- EfficientNet-B0
- (Optional: MobileNetV2, VGG16, Custom CNN)

---

## Imbalance Handling Techniques

- Weighted Random Sampler
- Class-weighted Cross Entropy
- Focal Loss
- Class-Balanced Loss
- Label Smoothing

---

## Evaluation Metrics

- Accuracy
- Top-5 Accuracy
- Balanced Accuracy
- Macro F1 Score
- Micro F1 Score
- Precision & Recall
- ROC-AUC (Macro)
- PR-AUC (Macro)
- G-Mean
- Confusion Matrix

---

## Model Complexity Analysis

- Number of Parameters
- FLOPs (MACs)
- Inference Time (ms)

---

## Feature Visualization

- PCA
- t-SNE
- UMAP
- Grad-CAM (model explainability)

---

## Transfer Learning

Models trained on Dataset A are fine-tuned and evaluated on Dataset B to measure generalization performance.

---

## How to Run

1. Open notebook in Google Colab
2. Enable GPU runtime
3. Download the Flowers dataset zip file from:
   https://www.kaggle.com/datasets/alxmamaev/flowers-recognition
4. Upload and unzip the Flowers dataset in Colab
5. Run all cells sequentially
6. Review generated plots and metrics

---

## Conclusion

This project demonstrates how class imbalance impacts model performance and how different architectures, loss functions, and sampling techniques affect classification accuracy and feature separability. Transfer learning improves generalization across datasets, and Grad-CAM helps interpret model decisions.
