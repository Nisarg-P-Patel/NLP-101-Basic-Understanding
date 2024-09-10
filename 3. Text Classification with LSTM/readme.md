# Text Classification with LSTM

This project demonstrates text classification using Long Short-Term Memory (LSTM) networks on a dataset of Department of Justice press releases. The notebook covers data preprocessing, feature extraction, LSTM model training, and evaluation.

## Features

- Data loading and preprocessing
- Text tokenization and stopword removal
- Stemming of tokens
- Sequence padding for LSTM input
- Model training using LSTM with embedding layer
- Model evaluation and performance metrics

## Dataset

The dataset used is from Kaggle: [Department of Justice 2009-2018 Press Releases](https://www.kaggle.com/datasets/jbencina/department-of-justice-20092018-press-releases). It contains press releases categorized by various components.

## Prerequisites

Ensure you have the following Python packages installed:

- `pandas`
- `numpy`
- `nltk`
- `tensorflow`

You can install these packages using pip:

```bash
pip install pandas numpy nltk tensorflow
