# SemEval Aspect-Based Sentiment Analysis with LLaMA-2

This project demonstrates how to perform **aspect-based sentiment analysis (ABSA)** using the **SemEval 2016 Task 5** dataset and **LLaMA-2 large language models** via Hugging Face Transformers. The model predicts the sentiment (positive, negative, neutral) for given aspect terms in sentences.

## Features
- Parses XML files from SemEval 2016 Task 5 for laptops and restaurants.
- Uses **LLaMA-2** (7B) for sentiment prediction.
- Provides a Hugging Face `pipeline` for text generation.
- Evaluates performance with **accuracy**, **macro F1**, **weighted F1**, and a **classification report**.
- Handles missing files, unknown predictions, and parsing errors.

## Requirements

```bash
python >= 3.10
pip install torch transformers pandas tqdm scikit-learn huggingface_hub
