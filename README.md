```markdown
# K-10 Report Analysis using NLP and Deep Learning

## 📌 Overview
This project builds a deep learning-powered engine that performs automated analysis of financial annual reports (like Reliance’s). It leverages Natural Language Processing (NLP) to extract insights from unstructured sections such as the Management Discussion and Analysis (MD&A), compute key financial ratios, and summarize high-impact themes and sentiments.

## 🧠 Objective
To develop an intelligent system that uses NLP and sequence models to analyze financial disclosures and predict the directional performance of companies over the next 5 years — accelerating decision-making compared to traditional manual analysis.

## 🔍 Core Features
- Automated extraction of textual data from PDFs
- Sentiment analysis using FinBERT & VADER
- Text summarization with BART
- Topic modeling using Gensim LDA
- Profit prediction using ML & DL models
- Interactive web app with chatbot (Flask)
- Data visualization of KPIs, sentiments, and predictions

## 🧰 Tech Stack
- Python, Flask, Jupyter Notebook
- NLP: SpaCy, NLTK, HuggingFace Transformers (BERT, BART)
- ML: scikit-learn, TensorFlow, Keras
- Topic Modeling: Gensim
- Frontend: HTML, CSS, JS (static folder)
- Visualization: matplotlib, seaborn, wordcloud

## 🧾 Project Structure
k10-report-nlp/
├── app.py
├── training_prediction_model.ipynb
├── requirements.txt
├── requirements_2.txt
├── data/
│ ├── archive/
│ ├── extracted_text/
│ ├── financial_statements.xlsx
│ ├── reliance_financials.csv
│ └── processed_data/
├── scripts/
├── static/
│ ├── images/
│ ├── css/
│ └── js/
├── templates/
│ └── index.html
└── README.md
