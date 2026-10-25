# AI Text – AI-Powered Text Processing Application

## Overview

AI Text is an AI-powered web application developed using Python, Streamlit, and Hugging Face Transformers. It provides intelligent text processing features through an interactive and user-friendly interface.

The application uses pretrained AI models to summarize text, translate languages, analyze sentiment, and answer questions based on the given context.

## Features

### 1. Text Summarization
- Summarizes lengthy text into concise and meaningful content.
- Uses a pretrained Hugging Face model.
- Displays the original and summarized word counts.

### 2. Language Translation
- Translates English text into French.
- Uses a pretrained machine translation model.

### 3. Sentiment Analysis
- Identifies positive and negative sentiments in text.
- Displays the predicted sentiment and confidence score.

### 4. Question Answering
- Accepts text as context and answers questions based on it.
- Displays the generated answer and confidence score.

## Technologies Used

- Python
- Streamlit
- Hugging Face Transformers
- PyTorch
- SentencePiece

## Project Structure

```text
AI-Text/
├── app.py
├── requirements.txt
└── README.md
```

## Installation and Setup

### Prerequisites
- Python 3.10 or later
- Visual Studio Code
- Internet connection

## AI Models Used

| Feature | Hugging Face Model |
|---|---|
| Text Summarization | sshleifer/distilbart-cnn-12-6 |
| Language Translation | Helsinki-NLP/opus-mt-en-fr |
| Sentiment Analysis | distilbert/distilbert-base-uncased-finetuned-sst-2-english |
| Question Answering | distilbert/distilbert-base-cased-distilled-squad |

## Applications

- Summarizing educational materials and articles.
- Translating English content into French.
- Analyzing customer reviews and feedback.
- Answering questions from textual information.
- Exploring Natural Language Processing applications.

## Future Enhancements

- Support for additional languages.
- Document upload functionality.
- Downloadable summaries and results.
- Additional AI-powered text processing features.

## Conclusion

AI Text demonstrates the practical application of Artificial Intelligence and Natural Language Processing using pretrained transformer models. It combines multiple text processing capabilities in a single Streamlit application.

