# Tweet Classification with NLP
Classify disaster-related tweets using DistilBERT, LSTM, and VADER sentiment

## Project Overview

To enhance disaster response efficiency, we developed a hybrid deep learning model leveraging DistilBERT embeddings and an LSTM architecture to classify disaster-related tweets. The objective was to automate real-time tweet classification for emergency management teams. Feature engineering played a key role, integrating one-hot encoding for keyword and location indicators, as well as sentiment scores using VADER.

The final model achieved **83% classification accuracy**, offering a scalable solution for natural disaster communication pipelines.

## Tech Stack
- Python (PyTorch, Transformers, scikit-learn, NLTK)
- Jupyter Notebook
- VADER Sentiment Analysis
- Pandas & NumPy

## Modeling Highlights
- Used DistilBERT transformer for tweet embeddings
- Combined with LSTM classifier for sequential text understanding
- Applied VADER for sentiment scoring as an auxiliary feature
- Engineered location and keyword-based one-hot encoded features
- Trained with balanced class handling and batch normalization

## Key Insights
- Tweets tagged with location and clear disaster keywords are easier to classify accurately
- Sentiment polarity helps distinguish panic or distress signals from neutral chatter
- Combining BERT-style embeddings with classical NLP features boosts accuracy

## Repository Contents
- `model`: Full modeling pipeline with training & evaluation
- `presentation `: Presentation slides
- `data`: [Kaggle Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started/data)



📍 Jan 2025 – Mar 2025  
🏫 Purdue University Daniels School of Business
