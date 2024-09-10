# Sentiment Analysis with NeMo

This project demonstrates sentiment analysis using NVIDIA NeMo, focusing on text classification with a pre-trained BERT-like model on the IMDB dataset.

## Features

- Data download and preprocessing
- Text classification model training using NeMo
- Configuration setup and experiment management
- Training and testing of the sentiment analysis model

## Dataset

The dataset used is the IMDB movie reviews dataset, available from Stanford's [sentiment dataset](https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz).

## Prerequisites

Ensure you have the following Python packages installed:

- `nemo_toolkit[nlp]`
- `wget`
- `torch`
- `pytorch_lightning`
- `omegaconf`

You can install the necessary packages using pip:

```bash
pip install git+https://github.com/NVIDIA/NeMo.git@r1.0.0rc1#egg=nemo_toolkit[nlp]
pip install wget torch pytorch_lightning omegaconf
