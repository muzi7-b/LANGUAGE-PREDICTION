 # LANGUAGE-PREDICTION
  
  Given a word or sentence as input, this project predicts which language the text
  is written in. It uses Natural Language Processing (NLP) to classify text across
  South Africa's 11 official languages.
  
  ## Overview
  
  South Africa is a multicultural society with 11 official languages. This project
  trains a machine learning model that identifies the language of a piece of text,
  using South African language texts for training.
  
  ## How it works
  
  1. **Preprocessing** — clean and normalize the input text (lowercasing,
     punctuation and noise removal) using `nltk`, `string`, and `re`.
  2. **Feature extraction** — convert text into numerical features with
     `TfidfVectorizer` from scikit-learn.
  3. **Classification** — a trained model predicts the language of the input text.
  
  ## Tech stack
  
  - **Data analysis:** pandas, numpy
  - **Visualization:** seaborn, matplotlib
  - **NLP / preprocessing:** nltk, re, string
  - **Modeling:** scikit-learn (TF-IDF + classifier)
  
  ## Getting started
  
  ### Prerequisites
  
  - Python 3.x
  - Jupyter Notebook
  
  ### Installation
  
  ```bash
  git clone https://github.com/muzi7-b/LANGUAGE-PREDICTION.git
  cd LANGUAGE-PREDICTION
  pip install pandas numpy seaborn matplotlib nltk scikit-learn
  
  Usage
  
  Open the notebook and run the cells:
  
  jupyter notebook "Language Prediction.ipynb"
  
  Enter a word or sentence when prompted, and the model returns the predicted language.
