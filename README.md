# Personalized-Cancer-Diagnosis
Project Overview
The goal of this project is to predict the type of cancer based on gene variation data and associated textual descriptions. The dataset contains both structured data (gene variations) and unstructured data (textual descriptions). This project explores different feature engineering techniques, such as Bag of Words and response coding, and uses machine learning models to achieve high prediction accuracy.
Dataset:
The dataset used in this project consists of gene variations and their corresponding text descriptions. The data is divided into training and testing sets:
Gene Variation Data: Contains categorical information about the gene mutations.
Textual Data: Descriptions of the gene variations provided in natural language.
Target: The dataset is labeled with nine possible classes representing different types of cancer.
Feature Engineering:
Feature engineering was crucial in this project due to the nature of the data:
Text Preprocessing: The textual data was cleaned by removing stop words, converting text to lowercase, and tokenizing the text.
Feature Extraction: Techniques like Bag of Words and response coding were used to extract features from the text.
Feature Selection: The importance of features was evaluated to select the most relevant ones for the model.
Modeling:
The following models were implemented and evaluated:
Naive Bayes: Chosen for its effectiveness in handling high-dimensional data like text.
Logistic Regression: Used for its interpretability and performance in binary and multiclass classification problems.
Model selection was based on the nature of the data and the need for efficient classification. Other models like Random Forest and Decision Trees were considered but not chosen due to their complexity and the interpretability of simpler models.
