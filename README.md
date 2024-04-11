# Overview

This phishing email classification project utilizes various machine learning models, including the pre-trained BERT (Bidirectional Encoder Representations from Transformers) model, for classifying emails as phishing (spam) or safe (non-spam). The script compares and evaluates the performance of different models, such as Logistic Regression, Decision Trees, Random Forests, Gradient Boosting, Naive Bayes, and Multi-Layer Perceptrons, to determine the best model for the given task. The email dataset used in this project is from Kaggle.

## Features

- **Data Preprocessing**: The script handles loading and preprocessing of email data from a CSV file, including label encoding and dataset splitting.
- **Custom Dataset Class**: A custom EmailDataset class is implemented to handle email data tokenization and preparation for input into the BERT model.
- **Model Comparison and Evaluation**: The script trains and evaluates various machine learning models, including Logistic Regression, Decision Trees, Random Forests, Gradient Boosting, Naive Bayes, and Multi-Layer Perceptrons, on the email classification task.
- **BERT Model Training**: The script trains a BERT model for sequence classification using the provided email data. It leverages PyTorch and the Hugging Face Transformers library for model training and optimization.
- **Evaluation Metrics**: Training and validation loss, accuracy, precision, recall, and F1-score are computed during the training process for each model.
- **Inference**: A predict function is provided to classify new emails as phishing or safe using the trained models.
- **Model Saving**: The trained models' states are saved for future use, allowing inference without retraining the models.
- **Explainability**: The script incorporates the LIME (Local Interpretable Model-Agnostic Explanations) library to provide explanations for the model's predictions on specific emails.


## License

This project is licensed under the MIT License. See the [LICENSE] (LICENSE) file for details.

---

**Authors**: Bohdan Boiprav & Catalin Bondari
