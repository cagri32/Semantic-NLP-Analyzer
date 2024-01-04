# Semantic NLP Analyzer

## Overview

Semantic NLP Analyzer is an advanced sentiment analysis project that leverages powerful Natural Language Processing (NLP) techniques to classify user reviews effectively. The project aims to discern the most effective methodology for classifying diverse-length and structured user reviews into Positive, Neutral, and Negative categories.

## Objective

The primary goal is to identify the optimal method between traditional Bag of Words (BOW) and advanced Text Embedding techniques. The selected method is applied to predict classifications for the entire Testing Dataset. The project recognizes the subjectivity in classifying user reviews and acknowledges potential misclassifications.

## Technologies Used

- Jupyter Notebook
- PyTorch
- CUDA
- Sentence Transformer library
- Various Language Models (e.g., all-mpnet-base-v2, multi-qa-mpnet-base-dot-v1, all-distilroberta-v1, all-MiniLM-L12-v2, multi-qa-distilbert-cos-v1, all-MiniLM-L6-v2)

## Experiments and Evaluations

### Text Embedding Approach

- Achieved a training set accuracy of 86.24% using the selected language model.
- Manual verification yielded an average accuracy of 70%.
- Considered runtime and accuracy, selecting all-mpnet-base-v2 as the final model for the Test Dataset prediction.

### Bag-of-Words (BOW) Approach

- Achieved a training set accuracy of 83.07% using Logistic Regression.
- Feature selection: Top 2000 features with the highest chi2 scores.
- Considered runtime and accuracy, favoring BOW for computational efficiency.

## Conclusion

The project provides a comparative analysis of Bag-of-Words and Text Embedding, emphasizing the trade-off between computational efficiency and classification accuracy. Bag-of-Words offers reasonable accuracy with faster runtime, while Text Embedding, especially using advanced language models, enhances accuracy at the cost of increased computational demands.

## Instructions to Run

Run the code blocks sequentially from the beginning to the end.

