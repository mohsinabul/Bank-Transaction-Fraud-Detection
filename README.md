# Fraud Detection in Financial Transactions using Deep Learning
This project focuses on detecting fraudulent financial transactions using deep learning models. The study compares the performance of Convolutional Neural Networks (CNNs), Long Short-Term Memory networks (LSTMs), and a Random Forest baseline on a real-world highly imbalanced dataset.

Project Structure
Report: Full academic report prepared in LaTeX with code snippets using the minted package.

Models:

CNN Model for spatial pattern detection

LSTM Model for sequential pattern analysis

Random Forest for traditional feature-based classification

Data Processing:

Feature scaling and selection

SMOTE oversampling to handle class imbalance

Evaluation:

5-Fold Cross-Validation

Precision and Recall as key metrics

Confusion matrix and feature importance visualizations

Key Findings
CNN achieved the highest accuracy and fastest training time.

LSTM performed competitively but was slower.

Random Forest remained a strong baseline without requiring GPUs.

SMOTE effectively balanced the dataset to improve minority class detection.

Future Work
Develop hybrid CNN-LSTM models.

Apply explainable AI techniques (SHAP, LIME) for model transparency.

Getting Started
This project is mainly documentation-based. If you wish to run the models:

Python 3.8+

Install required libraries:

bash
Copy
Edit
pip install tensorflow scikit-learn imbalanced-learn matplotlib seaborn

Author
Abul Mohsin

Department of Computing, Atlantic Technological University

Email: l00187574@atu.ie
