# 📰 Fake News Detection using BERT

## 📌 Project Overview

This project uses Google's BERT (Bidirectional Encoder Representations from Transformers) model to classify news articles as **Real** or **Fake** using Deep Learning and Natural Language Processing (NLP).

The model is fine-tuned on a labeled fake news dataset using Hugging Face Transformers and PyTorch.

---

## 🚀 Features

- Deep Learning-based Fake News Detection
- BERT Transformer Model
- Text Tokenization using BERT Tokenizer
- Fine-tuning with PyTorch
- Model Evaluation
- Save & Reload Trained Model
- Predict News from Custom Input

---

## 🛠 Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- BERT
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📂 Dataset

The dataset contains labeled news articles.

Labels:

- 0 → Fake News
- 1 → Real News

---

## 🧠 Model Architecture

Dataset

↓

Text Cleaning

↓

BERT Tokenizer

↓

BERT Base Uncased

↓

Linear Classification Layer

↓

Prediction

---

## 📈 Results

- Model: BERT Base Uncased
- Training Epochs: 2
- Optimizer: AdamW
- Accuracy: 99.91%

---

## 💻 Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Run

Open

```
Fake_News_Detection.ipynb
```

Run all cells.

---

## 📌 Example Prediction

Input:

```
NASA launched a new satellite successfully.
```

Output:

```
Real News
```


---

![alt text](accuracy.png)
![alt text](prediction.png)

## 👩‍💻 Author

Muskan Jaiswal

LinkedIn: https://www.linkedin.com/in/muskan-jaiswal-62a995330/

GitHub: https://github.com/Muskan2005126