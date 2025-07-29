Fake and Real News Dataset:

 Objective
To build machine learning models that classify whether a news article is fake or real, using labeled text data.

Dataset Overview:
Feature	Description
Files	Fake.csv (~23,500 records), True.csv (~21,400 records)
Columns	title, text, subject, date
Total	~44,900 news articles
Labels	Binary (Fake = 0, Real = 1)
Balance	Nearly equal distribution of fake vs real articles.

Preprocessing Steps:
Combine title and text (content = title + text)

Lowercase text

Remove punctuation, stopwords, digits

Tokenize and apply lemmatization or stemming

Feature Engineering:
Bag-of-Words

TF-IDF Vectorization

Word Embeddings (Word2Vec, GloVe)

Contextual Embeddings (BERT, RoBERTa)

Common Models Used:
Model Type	Example Algorithms	Accuracy (Typical)
Traditional ML	Logistic Regression, SVM, RF	~90–95%
Deep Learning	LSTM, Bi-LSTM, GRU	~94–97%
Transformers	BERT, DistilBERT	~97–99%

Use Cases:
Fake news detection tools

Social media content moderation

NLP model benchmarking.

# COLAB LINK https://colab.research.google.com/drive/1Q1D8YqFeF8Fy0-zf6innF-ItTd7VXDWi#scrollTo=uz4aLJIs8MUD

