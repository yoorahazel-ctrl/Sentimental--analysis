# Sentimental--analysis
# 🤖 AI-Powered Sentiment Analyzer

An interactive web application built with **Python**, **Streamlit**, and **Hugging Face Transformers** that evaluates customer reviews, social media posts, or any custom text to classify its underlying sentiment (`POSITIVE` or `NEGATIVE`) in real time.

## ✨ Features
* **Deep Learning NLP Engine:** Powered by a pre-trained DistilBERT model (`distilbert-base-uncased-finetuned-sst-2-english`) to capture sentence context and nuance.
* **Interactive Web Interface:** Clean, browser-based UI built with Streamlit for instant text analysis.
* **Memory Optimization:** Uses `@st.cache_resource` to keep the transformer model loaded in memory, preventing redundant downloads and ensuring fast predictions.
* **Confidence Metrics:** Displays formatted percentage confidence scores alongside an expandable view of the raw JSON inference data.

## 🛠️ Tech Stack
* **Language:** Python
* **Machine Learning / NLP:** Hugging Face `transformers`, PyTorch (`torch`)
* **Frontend / Web Server:** Streamlit

## 🚀 Local Setup & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git)
   cd YOUR-REPO-NAME
