
# Custom NLP Spam Detection Model with TensorFlow

This repository contains a custom NLP model for spam detection implemented in TensorFlow. The model uses LSTM with custom word embeddings to classify messages as spam or not. 

## Key Components

- **Word Embeddings:** Custom embeddings capture domain-specific knowledge for better text analysis.
- **LSTM Layer:** Long Short-Term Memory networks for sequence analysis.
- **GlobalMaxPooling1D Layer:** Extracts essential features from sequences. This layer aggregates critical information from all hidden states within the sequences, providing valuable insights cumulatively.
- **Usage:** Train the model, evaluate its performance, and use it for spam detection.

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Pandas 

