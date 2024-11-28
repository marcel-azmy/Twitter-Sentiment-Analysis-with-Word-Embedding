# Twitter-Sentiment-Analysis-with-Word-Embedding

This project focuses on generating word embeddings from a Twitter dataset using Word2Vec, Doc2Vec, and CNN-based embedding techniques. The goal is to transform tweets into dense vector representations for semantic understanding, aiding in various natural language processing (NLP) tasks.

## Objective
To apply and evaluate different word embedding techniques for representing textual data in a high-dimensional vector space.

## Techniques Used
- **Word2Vec**: Generates word-level embeddings capturing contextual relationships.
- **Doc2Vec**: Creates document-level embeddings for entire tweets.
- **CNN-Based Embeddings**: Uses convolutional neural networks to extract meaningful features from text.

## Methodology
1. **Data Preprocessing**:
   - Cleaning and tokenizing tweets.
   - Removing stop words, punctuation, and special characters.

2. **Embedding Generation**:
   - Training Word2Vec and Doc2Vec models.
   - Implementing CNN for feature extraction.

3. **Evaluation**:
   - Visualizing embeddings using dimensionality reduction (e.g., t-SNE).
   - Assessing embedding quality in downstream tasks like clustering or classification.

## Tools and Libraries
- Python
- NumPy, Pandas
- Gensim (for Word2Vec and Doc2Vec) & nltk
- TensorFlow/Keras (for CNN)
- Scikit-learn (for evaluation and visualization)

## Use Cases
- **Sentiment Analysis**: Understand sentiment in tweets.
- **Text Classification**: Categorize tweets into topics or categories.
- **Clustering**: Group tweets with similar contexts.
