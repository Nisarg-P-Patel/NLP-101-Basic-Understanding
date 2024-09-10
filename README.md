# NLP 101: Basic-Understanding

Welcome to **NLP 101: Basic Understanding**, a comprehensive project showcasing fundamental text classification techniques and tools in Natural Language Processing (NLP). This project is divided into multiple parts, each exploring a different approach to text classification. 

## Project Overview

The project is structured into the following parts:

1. **[NLP with NLTK](https://github.com/Nisarg-P-Patel/NLP-101-Basic-Understanding/tree/main/1.%20NLP%20with%20NLTK)** 
   - This section covers fundamental NLP techniques using the Natural Language Toolkit (NLTK) in Python. It introduces basic preprocessing tasks such as tokenization, stopword removal, stemming, and term frequency analysis.
   - **Features:**
      - Tokenization of text documents
      - Lowercasing and stopword removal
      - Stemming using PorterStemmer
      - Word-document matrix creation
      - Term frequency calculation and visualization
      - Document frequency calculation and visualization
       
2. **[Text Classification Basics](https://github.com/Nisarg-P-Patel/NLP-101-Basic-Understanding/tree/main/2.%20Text%20Classification%20basic)**
   - In this section, you will learn how to perform text classification using various machine learning models on a dataset of Shakespeare's plays. The focus is on data preprocessing, feature extraction, and model evaluation.
   - **Features:**
     - Data loading and preprocessing
     - Text tokenization and stopword removal
     - Stemming of tokens
     - Feature extraction using _CountVectorizer_
     - Model training with Random Forest, SVM, and Logistic Regression
     - Model evaluation and performance metrics
     - Visualization of word clouds and play counts

3. **[Text Classification with LSTM](https://github.com/Nisarg-P-Patel/NLP-101-Basic-Understanding/tree/main/3.%20Text%20Classification%20with%20LSTM)
**
   - This part explores text classification using Long Short-Term Memory (LSTM) networks on a dataset of Department of Justice press releases. It includes steps for data preprocessing, sequence padding, and LSTM model training.
   - **Features:**
     - Data loading and preprocessing
     - Text tokenization and stopword removal
     - Stemming of tokens
     - Sequence padding for LSTM input
     - Model training using LSTM with embedding layer
     - Model evaluation and performance metrics
     
4. **[Text Classification for Sentiment Analysis with NEMO](https://github.com/Nisarg-P-Patel/NLP-101-Basic-Understanding/tree/main/4.%20Text%20Classification%20for%20Sentiment%20Analysis%20with%20NEMO)
**
   - This section demonstrates sentiment analysis using NVIDIA NeMo, featuring a pre-trained BERT-like model on the IMDB dataset. The focus is on setting up and training a sentiment analysis model.
   - **Features:**
     - Data download and preprocessing
     - Text classification model training using NeMo
     - Configuration setup and experiment management
     - Training and testing of the sentiment analysis model
   
## Dependencies

To run the notebooks and scripts, you will need the following dependencies:

- **NLP with NLTK**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `nltk`
  - `wordcloud`
  - `matplotlib`
  - `PIL`

- **Text Classification Basics**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `nltk`
  - `matplotlib`

- **Text Classification with LSTM**:
  - `pandas`
  - `numpy`
  - `nltk`
  - `tensorflow`
  - `pytorch`
  - `pytorch-lightning`

- **Text Classification for Sentiment Analysis with NEMO**:
  - `pandas`
  - `numpy`
  - `nltk`
  - `torch`
  - `pytorch-lightning`
  - `wget`
  - `omegaconf`
  - `nemo_toolkit`

You can install the necessary dependencies using `pip`. For example:

```bash
pip install pandas numpy scikit-learn nltk wordcloud matplotlib tensorflow torch pytorch-lightning wget omegaconf nemo_toolkit
```


