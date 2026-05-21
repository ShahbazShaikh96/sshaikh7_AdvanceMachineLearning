# Cats vs Dogs Image Classification: CNN From Scratch vs VGG16 Transfer Learning

This assignment compares image classifiers trained from scratch against transfer-learning models using the Microsoft Cats vs Dogs dataset.

## Objective

The goal is to understand how training data size affects model performance and how pretrained convolutional networks compare with custom CNNs.

## Main Work

- downloads and prepares the Cats vs Dogs image dataset
- builds training, validation, and test image directories
- trains custom CNN models from scratch
- trains pretrained VGG16-based transfer-learning models
- compares performance across different training sizes
- summarizes test accuracy and test loss across experiments

## Experiment Design

The notebook evaluates:

- CNNs trained from scratch with different sample sizes
- VGG16 transfer-learning models with different sample sizes
- performance gains from increasing training data
- performance gap between scratch models and pretrained models

## Key Result

The pretrained VGG16 transfer-learning approach performs strongest overall, especially when training data is limited. The custom CNN improves as more training data is added, but transfer learning remains more efficient and accurate in the reported experiments.

## Files

- `Cats_vs_Dogs_CNN_vs_VGG16_Transfer_Learning.ipynb`: full notebook with CNN and transfer-learning experiments
- `Cats_vs_Dogs_CNN_vs_VGG16_Transfer_Learning_Report.pdf`: rendered report
- `Unused_Empty_Assignment_2_Placeholder.txt`: empty placeholder retained from the original repository
