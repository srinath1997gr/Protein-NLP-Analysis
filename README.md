# Protein Sequence Classification: BERT vs. DistilProtBERT

This project compares the performance of **BERT** and **DistilProtBERT** on protein sequence classification using the SignalP dataset. Both models are fine-tuned and integrated with a custom classifier, with results analyzed for accuracy and efficiency.

## Features
- **BERT**: A general-purpose transformer fine-tuned for protein sequences.
- **DistilProtBERT**: A lightweight version of BERT optimized for protein tasks.
- **Custom Classifier**: A multi-layer neural network for binary classification.
- **Performance Comparison**: Validation and test accuracy metrics.

## Dataset
- **Source**: SignalP dataset for protein sequence classification.
- **Preprocessing**: Tokenized, padded, and truncated sequences for uniform input dimensions.

## Model Overview
- **BERT**: Contextualized embeddings for high accuracy.
- **DistilProtBERT**: Faster training with fewer parameters.
- **Classifier**: Three fully connected layers with dropout for regularization.

## Results

| Metric               | BERT      | DistilProtBERT |
|----------------------|-----------|----------------|
| Validation Accuracy  | 74.32%    | 70.28%         |
| Test Accuracy        | 85.41%    | 83.77%         |
| Training Time        | Higher    | Lower          |

## Liscense

This assignment is done in university of colorado Denver under Prof Farnoush Banaei-Kashani.
