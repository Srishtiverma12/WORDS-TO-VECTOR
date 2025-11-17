# WORDS-TO-VECTOR
📌 Overview

This project demonstrates how words can be converted into numerical vector representations using Word Embedding techniques. These embeddings capture semantic meaning, relationships, and context between words.
The entire workflow is implemented in Google Colab, making it easy to run without local setup.

🚀 Features

Preprocessing text data

Tokenization

Word Embedding techniques:

Word2Vec (CBOW & Skip-Gram)

GloVe Embeddings

TF-IDF Vectorization

One-Hot Encoding

Visualization using PCA / t-SNE

Easy to run on Google Colab

🧩 Technologies Used

Python 3

Google Colab

NumPy

Pandas

NLTK / SpaCy

gensim

scikit-learn

matplotlib / seaborn

📘 Concepts Covered
🔹 1. Tokenization

Converting raw text into tokens for processing.

🔹 2. One-Hot Encoding

Simple binary vector representation.

🔹 3. TF-IDF Vectorization

Captures importance of words across documents.

🔹 4. Word2Vec

Using gensim to train two models:

CBOW (Continuous Bag of Words)

Skip-Gram

🔹 5. Pre-Trained Embeddings

Load GloVe / Google News Word2Vec models.

🔹 6. Visualization

Project high-dimensional vectors into 2D using PCA/T-SNE.

📊 Results

Word similarity demonstration (model.similarity("king", "queen"))

Word analogies (king - man + woman = queen)

Vector visualizations for semantic clusters
