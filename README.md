# 📺 YouTube Video Summarizer using Machine Learning / AI

This project implements an end-to-end pipeline for summarizing YouTube videos using machine learning and natural language processing (NLP) techniques. The system extracts the transcript of a video and generates a concise summary, making it easier to consume long-form content efficiently.

## 🚀 Features

- 📄 Extracts transcripts from YouTube videos using `yt_dlp`
- 🧠 Uses state-of-the-art language models (e.g., HuggingFace transformers) for summarization
- 🧪 Preprocessing pipeline including text cleaning, tokenization, and batching
- 📊 Jupyter Notebook format for easy experimentation
- 📦 Optionally supports integration with OpenAI/GPT-based summarizers

## 🛠️ Tech Stack

- Python 3.8+
- Jupyter Notebook
- HuggingFace Transformers
- NLTK / spaCy / or other NLP libraries
- `yt_dlp` for downloading video transcripts
- `tqdm`, `numpy`, `pandas` for data handling and visualization
  
pip install transformers yt_dlp pandas numpy tqdm

🧪 How It Works
Enter the URL of a YouTube video.

The system extracts the transcript using yt_dlp.

The transcript is cleaned, chunked, and tokenized.

A pre-trained summarization model is applied (e.g., BART, T5).

The final output is a human-readable summary of the video content.


