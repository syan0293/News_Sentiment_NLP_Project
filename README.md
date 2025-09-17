# Project Overview
This project explores the application of Machine Learning and Deep Learning methods to classify news articles into categories based on their textual content.
I implemented and compared traditional ML algorithms (Random Forest, Gradient Boosting) with modern NLP models (CNN, LSTM, Transformer-based models like DistilBERT).

The goal was to evaluate the trade-off between accuracy, interpretability, and computational efficiency across different approaches.

# Key Contributions
- Conducted exploratory data analysis (EDA) to identify class imbalance, word distributions, and text length characteristics.

- Implemented text preprocessing & feature engineering, including tokenization, Bag-of-Word (BoW), stopword removal, and TF-IDF vectorization.

- Developed and benchmarked multiple models:

  - *Classical ML*: Random Forest, Gradient Boosting (achieved highest F1 score: 0.971)

  - *Deep Learning*: Feedforward Neural Networks, CNNs, LSTMs (F1 ~0.85–0.90)

  - *Transformers*: Fine-tuned DistilBERT (F1: 0.951)

- Optimized models with hyperparameter tuning (Grid Search, Random Search, dropout rates, learning rates).

- Designed clear performance comparison reports with metrics (weighted F1 score, accuracy) to highlight model strengths and weaknesses.

# Tech Stack & Skills
- Languages & Libraries: Python, Pandas, NumPy, Scikit-learn, Matplotlib, PyTorch, Keras, Transformers

- Core Techniques:

  - Text preprocessing (tokenization, stopwords, lemmatization)

  - Feature engineering (TF-IDF, Bag-of-Words, word count features)

  - Model training & evaluation (Random Forest, Gradient Boosting, CNN, LSTM, Transformer)

  - Hyperparameter tuning & performance optimization

- Other Skills: Data visualization, EDA, reporting model comparisons, balancing interpretability and performance
