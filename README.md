# GLCM Features and Classifier Evaluation

## What  
This project provides a framework to extract GLCM (Gray-Level Co-Occurrence Matrix) features from images and evaluate classification performance using two machine learning algorithms:  

- **K-Nearest Neighbors (KNN)**  
- **Support Vector Machine (SVM)**  

The repository includes modularized functions to:  
- Generate GLCM statistics from image datasets.  
- Train and evaluate classifiers with customizable parameters.  
- Display accuracy results for better interpretability.  

---

## How  

### Prerequisites  
Ensure you have the following libraries installed:  
- `numpy`  
- `sklearn`  
- `cv2` (OpenCV)  
- `skimage`  
- `matplotlib` (optional, for visualization)  

### Steps to Use  

#### Prepare Dataset  
- The dataset should be in the format of labeled image pairs.  

#### Feature Extraction  
- Use `generateGlcmStatistics` to extract GLCM features from images.  

#### Train Classifiers  
- Train a KNN classifier using `trainKnnClassifierWithNeighbours`.  
- Train an SVM classifier using `trainSvmClassifierWithKernel`.  

#### Evaluate Performance  
- Evaluate classifiers using respective evaluation methods and display accuracy.  

#### Custom Parameters  
- Adjust the number of neighbors for KNN or the kernel type for SVM to optimize results.  

---

## Why  
The purpose of this project is to:  
1. **Enhance Image Classification**: By leveraging GLCM statistics, the project extracts texture-based features, which are useful for image-based tasks.  
2. **Simplify Workflow**: Modularized methods enable easy experimentation with different features and parameters.  
3. **Provide Flexibility**: Supports customization of parameters like `n_neighbors` for KNN and `kernel` for SVM, empowering users to optimize classification accuracy for their datasets.  

This repository is ideal for anyone learning about GLCM feature extraction and classifier evaluation, or for researchers seeking a starting point for texture-based image classification tasks.  
