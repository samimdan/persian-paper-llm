# persian-paper-llm
# Persian Paper LLM | مدل زبانی فارسی برای تولید متن علمی

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![FastText](https://img.shields.io/badge/FastText-Embeddings-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

</div>

---

# 🇮🇷 معرفی پروژه

این پروژه یک **مدل زبانی فارسی (Persian Language Model)** مبتنی بر **BiLSTM** است که برای:

* پیش‌بینی کلمه بعدی
* تولید متن فارسی
* تولید متن علمی و دانشگاهی
* تحلیل الگوهای متنی

طراحی شده است.

مدل با استفاده از:

* PyTorch
* FastText Persian Embeddings
* BiLSTM

پیاده‌سازی شده و روی متن پایان‌نامه فارسی آموزش می‌بیند.

---

# 🇬🇧 Project Overview

This project is a **Persian Language Model** based on **BiLSTM** designed for:

* Next Word Prediction
* Persian Text Generation
* Scientific/Academic Text Generation
* Sequential Text Pattern Learning

The model is implemented using:

* PyTorch
* Persian FastText Embeddings
* BiLSTM Neural Networks

and trained on Persian thesis documents.

---

# ✨ Features

## 🇮🇷 قابلیت‌ها

* تولید متن فارسی
* پیش‌بینی کلمه بعدی
* استفاده از FastText فارسی
* پشتیبانی از فایل Word
* آموزش با PyTorch
* تولید متن علمی
* BiLSTM دوطرفه
* Early Stopping

---

## 🇬🇧 Features

* Persian text generation
* Next-word prediction
* Persian FastText embeddings
* Word document support
* PyTorch implementation
* Scientific text generation
* Bidirectional LSTM
* Early stopping support

---

# 🧠 Model Architecture

```text
Word Document
      ↓
Text Cleaning
      ↓
Tokenization
      ↓
FastText Embedding
      ↓
BiLSTM Network
      ↓
Next Word Prediction
      ↓
Generated Persian Text
```

---

# 📂 Project Structure

```bash
persian-paper-llm/
│
├── rnn.ipynb
├── thesis1.docx
├── cc.fa.300.bin
├── README.md
└── requirements.txt
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/USERNAME/persian-paper-llm.git
cd persian-paper-llm
```

---

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 📦 Required Packages

```txt
torch
gensim
python-docx
scikit-learn
numpy
```

---

# 📥 Download Persian FastText Model

Download Persian FastText embeddings:

https://fasttext.cc/docs/en/crawl-vectors.html

File needed:

```text
cc.fa.300.bin
```

Place it inside project folder.

---

# 🚀 Usage | نحوه استفاده

## 🇮🇷 آموزش مدل

فایل پایان‌نامه خود را داخل پروژه قرار دهید:

```text
thesis1.docx
```

سپس نوت‌بوک را اجرا کنید:

```bash
jupyter notebook rnn.ipynb
```

---

## 🇬🇧 Train the Model

Place your thesis/document file:

```text
thesis1.docx
```

Run notebook:

```bash
jupyter notebook rnn.ipynb
```

---

# ✍️ Text Generation Example

## Input

```python
seed = "تحلیل و شناسایی الگوهای"
```

## Output

```text
تحلیل و شناسایی الگوهای پویا و در این حوزه و سپس تحلیل ...
```

---

# 🧪 Technologies Used

* Python
* PyTorch
* FastText
* BiLSTM
* NLP
* Deep Learning

---

# 📈 Future Improvements

## 🇮🇷

* استفاده از Transformer
* استفاده از GPT فارسی
* بهبود کیفیت تولید متن
* اضافه کردن Beam Search
* آموزش روی دیتاست بزرگ‌تر

---

## 🇬🇧

* Transformer-based architecture
* Persian GPT integration
* Better text diversity
* Beam search decoding
* Larger dataset training

---

# 🤝 Contribution

Pull requests are welcome.

For major changes, please open an issue first.

---

# 📜 License

MIT License

---

# 👨‍💻 Author

Developed by Sami

GitHub:
https://github.com/samimdan

---
