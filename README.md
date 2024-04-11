# Overview

This repository contains a Python script that utilizes the pre-trained BERT (Bidirectional Encoder Representations from Transformers) model for classifying emails as phishing (spam) or safe (non-spam). The script is designed to preprocess email data, train a BERT model, and provide inference capabilities for classifying new emails.

## Features

- Data Preprocessing: The script handles loading and preprocessing of email data from a CSV file, including label encoding and dataset splitting.
- Custom Dataset Class: A custom EmailDataset class is implemented to handle email data tokenization and preparation for input into the BERT model.
- BERT Model Training: The script trains a BERT model for sequence classification using the provided email data. It leverages PyTorch and the Hugging Face Transformers library for model training and optimization.
- Evaluation Metrics: Training and validation loss, accuracy, precision, recall, and F1-score are computed during the training process.
- Inference: A predict function is provided to classify new emails as phishing or safe using the trained BERT model.
- Model Saving: The trained BERT model's state is saved to a file for future use, allowing inference without retraining the model.

## Requirements

To run this script, you'll need the following dependencies:

- Python 3.6 or later
- PyTorch
- Transformers (from Hugging Face)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Wordcloud
- Tqdm
  
## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Authors**: Bohdan Boiprav & Catalin Bondari
