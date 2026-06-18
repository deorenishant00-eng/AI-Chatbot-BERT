# AI-Chatbot-BERT
 BERT-powered AI Chatbot built with Python, Streamlit, PyTorch, and NLP techniques for intelligent question answering using semantic similarity and transformer-based language understanding.


# Project Overview
AI Chatbot BERT is a Natural Language Processing (NLP) project developed using Python, Streamlit, PyTorch, and the BERT (Bidirectional Encoder Representations from Transformers) model. The chatbot is designed to understand user queries and provide intelligent responses by leveraging the contextual language understanding capabilities of BERT.

The application features an interactive web-based user interface built with Streamlit, allowing users to communicate with the chatbot in real time. To enhance the visual experience, a custom background image is integrated into the application using CSS and Base64 image encoding.

The chatbot uses the pre-trained bert-base-uncased model from the Hugging Face Transformers library. User input is converted into BERT embeddings, which capture the semantic meaning of the text. The system then compares these embeddings with a predefined set of question embeddings using Cosine Similarity. Based on the similarity score, the chatbot identifies the most relevant question and returns the corresponding response.

This project demonstrates the practical application of transformer-based language models in conversational AI systems. It showcases concepts such as text embedding generation, semantic similarity matching, natural language understanding, and interactive web application development.

### Key Features

* BERT-based Natural Language Understanding
* Interactive chatbot interface using Streamlit
* Semantic search using Cosine Similarity
* Predefined question-answer knowledge base
* Real-time response generation
* Custom user interface with background image support
* Efficient embedding computation with PyTorch
* Cached model loading for improved performance

### Technologies Used

* Python
* Streamlit
* Hugging Face Transformers
* BERT (bert-base-uncased)
* PyTorch
* Scikit-learn
* NumPy
* Base64 Encoding

This project serves as a beginner-to-intermediate level implementation of conversational AI and demonstrates how modern transformer models can be used to build intelligent chatbot applications capable of understanding user intent and delivering context-aware responses.
