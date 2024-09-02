# Music Genre Classification with PCA and Logistic Regression

<p align="center" width="100%">
    <img width="60%" src="https://images.unsplash.com/photo-1507838153414-b4b713384a76?q=80&w=1770&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">
</p>


### Table of Contents
1. [Overview](#overview)
2. [Project Steps](#projectsteps)
4. [Features](#features)
3. [Results](#results)
5. [Usage](#usage)

## Overview<a name="overview"></a>
This project involves classifying music tracks into different genres using machine learning techniques. The dataset consists of various musical features and genre labels. 
The goal is to predict genres for tracks with missing genre information by leveraging principal component analysis (PCA) and logistic regression.

## Project Steps<a name="projectsteps"></a>
1. **Data Exploration and Preparation**
* Loaded and examined the dataset to understand its structure and identify missing values.
* Investigated the distribution of genres to ensure balanced representation.

2. **Principal Component Analysis (PCA)** 
* Standardized the feature data and applied PCA to reduce dimensionality.
* Determined the optimal number of principal components based on the cumulative variance explained.

3. **Model Training and Evaluation**
* Trained logistic regression models using both PCA-transformed features and original features.
* Compared the performance of the models based on accuracy and classification reports.

4. **Genre Prediction and Data Completion**
* Used the more effective model to predict genres for tracks with missing genre information.
* Updated the original dataset with predicted genres to complete the genre information.

## Features<a name="features"></a>
* **Data Standardization:** Ensured consistent scaling of features before applying PCA.
* **Dimensionality Reduction:** Used PCA to reduce the number of features while retaining essential information.
* **Model Evaluation:** Compared logistic regression models trained on PCA-transformed and original features.
* **Genre Prediction:** Filled in missing genre labels using the trained model.

## Results<a name="results"></a>
* The performance of the logistic regression model was assessed, and the optimal number of principal components was determined.
* Missing genre information in the dataset was accurately predicted and integrated.

## Usage<a name="usage"></a>
To replicate the analysis:

1. Clone the repository.
2. Ensure you have the required Python packages installed (e.g., pandas, scikit-learn, seaborn, matplotlib).
3. Follow the steps outlined in the Jupyter notebooks or Python scripts to load the data, perform PCA, train the models, and make predictions.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.
