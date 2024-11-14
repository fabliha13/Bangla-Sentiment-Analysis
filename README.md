# Bangla-Sentiment-Analysis
A comprehensive project on Bangla sentiment analysis using the SentNoB dataset, exploring the performance of BERT-based models and handcrafted lexical features for Bangla text classification.


This repository contains the code, dataset, paper, and presentation slides for our project on sentiment analysis for Bangla language data. Using SentNoB, an annotated dataset of public Bangla comments, we fine-tuned several Transformer-based models to benchmark Bangla-specific sentiment analysis.

## Project Overview

Analyzing public sentiment in under-resourced languages like Bangla is crucial for expanding natural language processing capabilities. Our study benchmarked multiple BERT-based models, including BanglaBERT and mBERT, and found that:

- **BanglaBERT** achieved the highest accuracy of 74.5%.
- Handcrafted lexical features performed better than both pre-trained and fine-tuned language models.

## Repository Structure

- **`code/`**: Contains Python scripts and Jupyter notebooks for data preprocessing, model training, and evaluation.
- **`dataset/`**: The SentNoB dataset used for training and evaluation.
- **`paper/`**: A PDF of our research paper titled "Sentiment Analysis of Bangla Social Media Comments."
- **`slides/`**: Presentation slides summarizing the project's objectives, methods, and findings.

## Requirements

- Python 3.8+
- Required libraries can be installed via:
  ```bash
  pip install -r requirements.txt
