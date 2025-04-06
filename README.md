# Analyzing the Effects of Data Degradation on Image Classification

## Overview
This project investigates the impact of various image preprocessing and transmission techniques on the performance of image classification models. With modern deep learning models relying on subtle image features for accurate classification, changes in image quality, such as compression or format conversion, can significantly affect model performance. This project aims to systematically analyze these effects and explore potential mitigation strategies.

## Main Goals
- Analyze the effects of compression algorithms (JPEG, PNG, WebP) on image classification.
- Study the impact of file conversion between image formats (JPEG, PNG, RAW, DCAM).
- Examine the influence of quantization artifacts and image transmission over a network.
- Evaluate the performance of classification models such as CNN using various datasets.

## Research Questions
1. How does image degradation affect the performance of deep neural networks (DNN)?
2. What methods can be used to eliminate or mitigate image degradation/artifacting effects on classification accuracy?
3. Can image degradation be used to improve any aspect of an image classification model?
4. How do neural networks perceive image degradations? How do humans perceive them? How are the perceptions similar or different?

## Datasets
- **ImageNet**: General images dataset.
- **HAM10000**: Medical images for skin lesion classification.
- **DICOM**: Medical image dataset in DICOM format.
- **MNIST** / **FMNIST**: One-channel images for digit and fashion classification.

## Models
The project will use pretrained **PyTorch** models for each dataset to evaluate the effects of image degradation and its impact on classification performance.

