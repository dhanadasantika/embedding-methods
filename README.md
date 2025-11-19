# Comparing Embedding Methods for Indonesian Text Classification
This project compares several embedding-based approaches for Indonesian text classification.

### Dataset : EmoT (Emotion – Twitter)  
source : https://github.com/IndoNLP/indonlu/tree/master/dataset/emot_emotion-twitter

### Two main categories of models are implemented:
**1. LSTM with Multiple Embedding Methods**
* LSTM + FastText
* LSTM + IndoBERT
* LSTM + mBERT

**2. Sentence Transformer + SVM**
* Uses a multilingual Sentence-BERT model to generate sentence-level embeddings.
* These embeddings are then fed into a Support Vector Machine (SVM) classifier to perform final emotion classification.
