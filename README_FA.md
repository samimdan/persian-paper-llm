# README_FA.md

<div align="left">

🇬🇧 English Version: [README.md](README.md)

</div>

# مدل زبانی فارسی برای تولید متن علمی

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![FastText](https://img.shields.io/badge/FastText-Embeddings-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

</div>

---

# معرفی پروژه

این پروژه یک مدل زبانی فارسی مبتنی بر BiLSTM است که برای:

* پیش‌بینی کلمه بعدی
* تولید متن فارسی
* تولید متن علمی و دانشگاهی
* تحلیل الگوهای متنی

طراحی شده است.

مدل با استفاده از:

* PyTorch
* FastText فارسی
* شبکه BiLSTM

پیاده‌سازی شده و روی متن پایان‌نامه فارسی آموزش می‌بیند.

---

# قابلیت‌ها

* تولید متن فارسی
* پیش‌بینی کلمه بعدی
* استفاده از FastText فارسی
* پشتیبانی از فایل Word
* پیاده‌سازی با PyTorch
* تولید متن علمی
* BiLSTM دوطرفه
* Early Stopping

---

# معماری مدل

```text
فایل Word
    ↓
پاکسازی متن
    ↓
توکن‌سازی
    ↓
FastText Embedding
    ↓
شبکه BiLSTM
    ↓
پیش‌بینی کلمه بعدی
    ↓
تولید متن فارسی
```

---

# ساختار پروژه

```bash
persian-paper-llm/
│
├── rnn.ipynb
├── thesis1.docx
├── cc.fa.300.bin
├── README.md
├── README_FA.md
└── requirements.txt
```

---

# نصب پروژه

## 1️⃣ کلون کردن ریپازیتوری

```bash
git clone https://github.com/USERNAME/persian-paper-llm.git
cd persian-paper-llm
```

---

## 2️⃣ نصب کتابخانه‌ها

```bash
pip install -r requirements.txt
```

---

# کتابخانه‌های موردنیاز

```txt
torch
gensim
python-docx
scikit-learn
numpy
```

---

# دانلود مدل FastText فارسی

لینک دانلود:

https://fasttext.cc/docs/en/crawl-vectors.html

فایل موردنیاز:

```text
cc.fa.300.bin
```

فایل را داخل پوشه پروژه قرار دهید.

---

# نحوه استفاده

فایل پایان‌نامه یا متن خود را داخل پروژه قرار دهید:

```text
thesis1.docx
```

سپس نوت‌بوک را اجرا کنید:

```bash
jupyter notebook rnn.ipynb
```

---

# نمونه تولید متن

## ورودی

```python
seed = "تحلیل و شناسایی الگوهای"
```

## خروجی

```text
تحلیل و شناسایی الگوهای پویا و در این حوزه ...
```

---

# تکنولوژی‌های استفاده شده

* Python
* PyTorch
* FastText
* BiLSTM
* NLP
* Deep Learning

---

# توسعه‌های آینده

* استفاده از Transformer
* استفاده از GPT فارسی
* بهبود کیفیت تولید متن
* اضافه کردن Beam Search
* آموزش روی دیتاست بزرگ‌تر

---

# مشارکت

Pull Request ها پذیرفته می‌شوند.

برای تغییرات بزرگ ابتدا Issue ثبت کنید.

---

# لایسنس

MIT License

---

# توسعه‌دهنده

توسعه داده شده توسط Sami

GitHub:
https://github.com/samimdan
