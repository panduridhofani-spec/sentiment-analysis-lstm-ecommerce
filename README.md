# 🚀 Sentiment Analysis on E-Commerce Reviews using Deep Learning (LSTM)

This project implements a **Sentiment Analysis system** to classify customer reviews from an e-commerce platform (Tokopedia) into **positive** and **negative** sentiments using a **Deep Learning approach with LSTM (Long Short-Term Memory)**.

The goal of this project is to demonstrate how Natural Language Processing (NLP) and deep learning can be applied to extract insights from unstructured customer feedback.

---

## 📌 Project Overview

Customer reviews contain valuable information about user satisfaction. However, manually analyzing thousands of reviews is inefficient.  
In this project, we build an automated sentiment classification model that can help understand customer opinions at scale.

This project covers:
- Text preprocessing and cleaning
- Automatic sentiment labeling based on ratings
- Tokenization and padding
- LSTM model training using TensorFlow/Keras
- Model evaluation using accuracy and confusion matrix

---

## 🗂️ Dataset

- **Source:** Tokopedia Product Reviews (Kaggle)
- **Attributes used:**
  - `text` → customer review
  - `rating` → product rating (1–5)

### 🎯 Sentiment Labeling
| Rating | Sentiment |
|--------|-----------|
1–2      | Negative  |
3        | Neutral (excluded) |
4–5      | Positive  |

Only positive and negative reviews are used for this project.

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib, Seaborn  
- Google Colab  

---

## ⚙️ Workflow

1. Load dataset from Google Drive
2. Data cleaning and preprocessing
3. Sentiment labeling
4. Train-test split
5. Tokenization & padding
6. Build LSTM model
7. Model training
8. Evaluation (accuracy & confusion matrix)
9. Manual prediction testing
10. Save trained model

---

## 🤖 Model Architecture

- Embedding Layer  
- LSTM Layer (128 units)  
- Dropout (0.5)  
- Dense Layer with Sigmoid activation  

Loss function: `binary_crossentropy`  
Optimizer: `adam`

---

## 📊 Results

The trained LSTM model achieves good performance on the test dataset, with:
- High accuracy
- Balanced precision and recall for both classes

Confusion matrix visualization is used to analyze classification results in more detail.

> 📌 *You can find the full training process and evaluation in the Google Colab notebook.*

---

## 📓 Google Colab Notebook

You can run and explore the full implementation here:  
👉 **Colab:** [PUT_YOUR_COLAB_LINK_HERE]

---

## 💻 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sentiment-analysis-lstm.git
