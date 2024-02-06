# Terrastack: Satellite Agri-Modeling

![Terrastack Logo](https://placehold.it/200x100)

## Overview

Terrastack is a machine learning project aimed at classifying the growth stages of crops using satellite imagery data. The primary objective is to develop a model that accurately categorizes crop growth stages into three classes: 'no_crop', 'growing', and 'lush'. The dataset comprises clipped raster images for 569 geographical grid cells (GIDs) spanning 12 agricultural months. 

## Dataset

The dataset consists of clipped raster images stored in the 'prospace_assignment' directory. These images are resized to a standard size of 128x128 pixels and preprocessed to ensure uniformity across the dataset. Additionally, the dataset contains ground-truth annotations for model training and evaluation, stored as a CSV file.

## Methodology

### Data Exploration

The project begins with a comprehensive exploration of the dataset to understand its characteristics, including spatial and temporal distributions of crop growth stages. This exploration helps in identifying potential challenges and insights crucial for subsequent steps.

### Feature Engineering

Preprocessing and feature engineering techniques are implemented to optimize model performance. This includes resizing images, normalization, dimensionality reduction using Principal Component Analysis (PCA), and clustering with K-Means to identify distinct clusters corresponding to different growth stages.

### Model Selection

Appropriate machine learning algorithms are chosen for crop growth stage classification based on the nature of the problem and dataset characteristics. The selected model is trained on the annotated dataset and evaluated using various metrics to assess its performance.

### Evaluation

The model's performance is evaluated using metrics such as accuracy, precision, recall, F1 score, silhouette score, and Davies-Bouldin index. These metrics provide insights into the model's ability to accurately classify crop growth stages and its robustness.

For code implementation and further details, refer to the provided code files in the repository.

## Conclusion

Terrastack aims to contribute to the field of precision agriculture by providing a reliable method for monitoring crop growth stages using satellite imagery data. By accurately classifying crop growth stages, this project can assist farmers and agricultural experts in making informed decisions and optimizing agricultural practices for improved productivity and sustainability.
