# 💠Sentiment Analysis using LSTM & Bi-LSTM

This repository contains two deep learning projects that perform sentiment analysis on text data using **Long Short-Term Memory (LSTM)** and **Bidirectional LSTM (Bi-LSTM)** models.
The goal is to classify text (such as reviews, comments, or tweets) into sentiment categories like **positive** or **negative**.

---

## 📂 Project Structure

- **Sentiment_anlysis_LSTM1.ipynb** → Implements a standard LSTM-based sentiment classifier.
- **Sentiment_anlysis_Bi-LSTM.ipynb** → Implements a Bidirectional LSTM-based sentiment classifier.
- Both models are trained, evaluated, and compared to understand the impact of bidirectional processing in recurrent neural networks.

---

## 🧠 Models Overview

### 1️⃣ LSTM Model
- Uses a single-direction LSTM layer.
- Captures context from **past words** only.
- Suitable for sequence data where earlier context strongly influences predictions.

### 2️⃣ Bi-LSTM Model
- Uses a **Bidirectional LSTM** layer.
- Captures context from **both past and future words** in a sentence.
- Often improves accuracy for tasks like sentiment analysis.

---

## 📊 Dataset
- The dataset contains text samples and their corresponding sentiment labels.\
- the link of dataset : https://www.kaggle.com/datasets/charunisa/chatgpt-sentiment-analysis
- Preprocessing steps include:
  - Text cleaning (removing special characters, numbers, and punctuation).
  - Tokenization & padding.
  - Converting labels to numerical form.

> 📌 Note: The dataset should be placed in the working directory or updated in the notebooks accordingly.

---


## 📈 Results

| Model       | Accuracy | Notes                                           |
|-------------|----------|-------------------------------------------------|
| **LSTM**    | 91.32%   | Baseline model.                                 |
| **Bi-LSTM** | 91.56%   | Improved context understanding, better performance.



