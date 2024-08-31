# Model_Performance_and_Comparison_NLP_with_IMDB_Movie_Reviews
This project demonstrates the application of Natural Language Processing (NLP) techniques and machine learning models to perform sentiment analysis on the IMDB movie review dataset. The goal is to classify movie reviews as either positive or negative based on their textual content.

## Features:
### Dataset:
The project uses a subset of the IMDB movie review dataset, consisting of 5000 reviews labeled as positive or negative.
### Natural Language Processing:

#### Text Vectorization:
Implemented both CountVectorizer and TfidfVectorizer to convert raw text into numerical features that can be used by machine learning models.
#### Word Embeddings:
Used Word2Vec from Gensim to generate word embeddings, capturing semantic meaning and relationships between words.
#### Topic Modeling:
Applied Latent Dirichlet Allocation (LDA) to discover underlying topics within the movie reviews.
### Machine Learning Models:

#### Support Vector Machine (SVM):
Implemented an SVM classifier to predict the sentiment of movie reviews. The model was trained using stratified k-fold cross-validation to ensure balanced class distribution.
#### Model Evaluation:
Evaluated the model’s performance using standard metrics such as accuracy, precision, recall, and F1-score.
### Tools and Libraries:

- **scikit-learn:** For machine learning models and data preprocessing.
- **Gensim:** For word embeddings with Word2Vec.
- **Pandas and NumPy:** For data manipulation and processing.
- **Matplotlib and Seaborn:** For visualizing data distributions and model performance.
## Objectives:
- To explore and implement various NLP techniques for processing and analyzing text data.
- To apply and compare different machine learning models for sentiment analysis.
- To gain insights into the performance and effectiveness of these models in real-world scenarios.
## How to Run:
1. Clone the repository to your local machine.
2. Install the necessary dependencies listed in the **requirements.txt**.
3. Run the Jupyter notebook to preprocess the data, train the models, and evaluate their performance.
## Conclusion:
This project provides a hands-on experience in applying NLP and machine learning to a practical problem: sentiment analysis. It highlights the importance of text preprocessing, the choice of features, and model selection in achieving accurate predictions. The techniques and models used in this project are widely applicable to various other text classification tasks.
