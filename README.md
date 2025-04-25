# Defect-Classificaition
Deep Learning for Defect Detection in Intimates Apparel


# 🧵 Deep Learning for Automated Garment Defect Detection

This repository contains the source code, model architecture, training logs, and supporting material for the research thesis:  
**"Deep Learning-Based Defect Detection in Intimates Clothing Manufacturing"** conducted as part of the Master’s in Data Science program.

## Project Overview

The garment industry relies heavily on manual inspection processes for quality control, which are often time-consuming, inconsistent, and error-prone. This project explores deep learning methods to automate defect detection using convolutional neural networks (CNNs), enabling scalable and real-time quality assurance in manufacturing.

The study focuses on both:
- **Binary classification**: Defective vs. Non-defective garments  
- **Multiclass classification**: Holes, Seam Puckering, Uncut Threads, Raw Edges, Broken Stitches

## Models Implemented

- ✅ **Baseline CNN**  
- 🔧 **Improved CNN** (with Batch Normalization & Dropout)  
- 🌱 **EfficientNetB0** (transfer learning with grayscale support)  
- 🧱 **ResNet18** (transfer learning with fine-tuning)

## Key Results

| Model           | Task         | Test Accuracy | F1-Score |
|----------------|--------------|----------------|----------|
| Baseline CNN   | Binary       | 86.59%         | 0.8036   |
| Improved CNN   | Multiclass   | **83.33%**     | **0.8312** |
| EfficientNetB0 | Multiclass   | 79.17%         | 0.7869   |
| ResNet18       | Binary       | **86.59%**     | **0.8567** |

## Folder Structure

Dataset:
-Single Classfication Dataset
-Multiclass Dataset
Codebase:
-Multi Class.ipynb
-Binary Classification.ipynb


## Explainability

Grad-CAM visualizations were used to enhance model transparency, showing clear class-discriminative regions in the garment images and supporting real-world interpretability.

## Thesis Highlights

- Trained and validated models using a proprietary dataset from MAS Intimates
- Compared performance across binary and multiclass tasks
- Addressed ethical concerns like data privacy and class imbalance
- Integrated model interpretability to support industrial deployment

## 🚀 Future Work

- Real-time integration into garment inspection pipelines
- Enhanced data augmentation and domain adaptation
- Broader dataset expansion across fabrics and production settings



