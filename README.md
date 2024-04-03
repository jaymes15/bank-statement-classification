# Bank Statement Description Classification

This project aims to classify bank statement descriptions into predefined categories using a machine learning approach. Bank statement descriptions often contain abbreviated or vague information, posing a challenge in interpreting their meaning. By classifying these descriptions into categories, financial institutions can enhance their analysis of transaction data for purposes such as fraud detection, customer segmentation, and trend analysis.

## Setup

To run this project, follow these steps:

1. **Create Environment**: Create a conda environment using the provided `environment.yml` file:
    ```
    conda env create --file environment.yml --name env
    ```

2. **Activate Environment**: Activate the newly created environment:
    ```
    conda activate env
    ```

3. **Start Jupyter Notebook**: Launch Jupyter Notebook to access and interact with the project files:
    ```
    jupyter notebook
    ```

## Project Overview

This Jupyter notebook contains the code for the bank statement description classification project. Here's an overview of the notebook's contents:

- **Data Preprocessing**: The dataset is preprocessed, including steps like tokenization, lowercasing, and removing stopwords.
  
- **Model Training**: Various machine learning algorithms such as Naive Bayes, Support Vector Machines (SVM), Logistic Regression, Random Forest, and Gradient Boosting are trained and evaluated for classification.

- **Evaluation**: The performance of trained models is evaluated using metrics such as accuracy, precision, recall, and F1-score on the test dataset. Confusion matrices and classification reports are also generated.

- **Deployment**: Once a satisfactory model is trained and evaluated, it can be deployed in production environments for real-time classification of bank statement descriptions.

## Conclusion

Bank statement description classification is a valuable task in financial analysis and management. By automating this process with machine learning techniques, financial institutions can streamline operations, improve decision-making, and enhance customer experience. This notebook serves as a guide to implementing such a classification system.
