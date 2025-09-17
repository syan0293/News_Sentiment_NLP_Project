# Sentiment & News Classification with Machine Learning and Deep Learning
## Project Overview
This project explores the application of Machine Learning and Deep Learning methods to classify news articles into categories based on their textual content.
I implemented and compared traditional ML algorithms (Random Forest, Gradient Boosting) with modern NLP models (CNN, LSTM, Transformer-based models like DistilBERT).

The goal was to evaluate the trade-off between accuracy, interpretability, and computational efficiency across different approaches.

## Key Contributions
- Performed exploratory data analysis (EDA) on news articles (category distribution, text length, vocabulary) to guide feature engineering and model design.

- Preprocessed text using tokenization, stopword removal, and vectorization (TF-IDF, Bag-of-Words) for ML models.

- Implemented and compared traditional ML (Random Forest, Gradient Boosting), deep learning (FNN, CNN, LSTM), and transformer (DistilBERT) approaches.

- Applied hyperparameter tuning & model evaluation using weighted F1 score, analyzing trade-offs in complexity, interpretability, and performance.

## Key Results
- **Random Forest** with TF-IDF achieved the best performance (Weighted F1 = 0.971), outperforming DL models (FNN 0.847, CNN 0.894, LSTM 0.897).

- **DistilBERT** fine-tuned model reached a **Weighted F1 of 0.951**, showing strong transformer performance but at higher computational cost.

- Demonstrated clear insights into when to prefer traditional ML vs deep learning, balancing accuracy, interpretability, and resource usage.

- Strengthened skills in text preprocessing, feature engineering, model comparison, and business communication.
