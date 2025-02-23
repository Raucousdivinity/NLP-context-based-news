# NLP-context-based-newsContext-Based News Recommendation System
Project Overview
The Context-Based News Recommendation System is a Python-based application that fetches real-time news articles and recommends the most relevant ones based on user input. It leverages Natural Language Processing (NLP) techniques to process and compare the relevance of news articles, making it easier for users to find news on topics they are interested in.

This project utilizes the NewsData.io API to fetch live news data and employs TF-IDF (Term Frequency-Inverse Document Frequency) and Cosine Similarity to rank articles based on their relevance to the user's search query.

How It Works
The user is prompted to enter a topic of interest.
The system fetches real-time news articles related to the topic.
The text from the news articles is preprocessed using NLP (tokenization, stopword removal).
The TF-IDF algorithm is used to convert text into numerical vectors.
Cosine similarity is calculated between the user input and the news articles.
The top 3 most relevant articles are recommended to the user.
