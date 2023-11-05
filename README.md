# ML Notebook

Welcome to the Machine Learning (ML) Notebook repository. This repository contains Jupyter notebooks related to various ML tasks and projects.

## Table of Contents

1. [CIFAR-10 Image Classification](classification/[CIFAR_10]Classification.ipynb)
   - **Description**: This notebook focuses on image classification using the CIFAR-10 dataset. It employs Linear Discriminant Analysis (LDA) for feature reduction and Logistic Regression for making predictions.
   - **Colab Link**: [Open in Google Colab](https://colab.research.google.com/github/DneshP/ML-Notebook/blob/master/classification/%CIFAR_10%Classification-CIFAR-10.ipynb)

2. [MNIST KNeighborsClassifier Image Classification](classification/[KNeighborsClassifier]ImageClassification.ipynb)
   - **Description**: This notebook focuses on image classification using the CIFAR-10 dataset. It employs the following feature reduction techniques:

     1. **Simple Standardization**:
        - A preprocessing step using StandardScaler to standardize the data.

     2. **Principal Component Analysis (PCA)**:
        - Standardization followed by PCA, reducing the dimensionality to 2 components.
        - `PCA` is a linear technique that can effectively capture variance in the data.

     3. **Linear Discriminant Analysis (LDA)**:
        - Standardization followed by LDA, reducing the dimensionality to 2 components.
        - `LDA` is a supervised technique that aims to maximize class separability.

     4. **Neighborhood Components Analysis (NCA)**:
        - Standardization followed by NCA, reducing the dimensionality to 2 components.
        - `NCA` is another supervised technique that focuses on preserving the relative neighborhood relationships.

   - **Colab Link**: [Open in Google Colab](https://colab.research.google.com/github/DneshP/ML-Notebook/blob/master/classification/%KNeighborsClassifier%ImageClassification.ipynb)

3. [SPAM Classifier](classification/SPAM_Classifier.ipynb)
   - **Description**: This notebook focuses on classifying spam and non-spam emails. It includes data preprocessing, model training, and evaluation.
   - **Colab Link**: [Open in Google Colab](https://colab.research.google.com/github/DneshP/ML-Notebook/blob/master/classification/SPAM_Classifier.ipynb)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.