#  Deep Learning Assignment – 2

This repository contains two deep learning projects developed as part of a sequence modeling assignment. Each explores a different technique for handling sequential data using modern neural architectures in TensorFlow and PyTorch.

---

##  Projects Overview

### 1️⃣ Seq2Seq Transliteration Model (Q1)

**Objective:**  
Build a character-level sequence-to-sequence (seq2seq) model that transliterates Hindi words written in Latin script (e.g., *dil*) into their correct Devanagari script (e.g., *दिल*).

**Key Features:**
- Encoder-decoder architecture with RNN, LSTM, or GRU cells
- Trained on the **Dakshina** dataset
- Handles preprocessing, training, evaluation, and interactive prediction
- Supports inference and reports transliteration accuracy
- Includes parameter count and training cost estimates

**Tools & Libraries:**
- Python 3.8+
- TensorFlow 2.x
- NumPy

📁 More details available in `seq2seq/README.md`

---

### 2️⃣ GPT-2 Lyrics Generator (Q2)

**Objective:**  
Fine-tune a GPT-2 model to generate creative English song lyrics based on a given prompt. The model learns lyrical structure and style from real-world lyrics.

**Dataset:**  
Trained on a custom lyrics dataset using Kaggle's [Poetry Dataset](https://www.kaggle.com/datasets/paultimothymooney/poetry), specifically focusing on Kanye West.

**Sample Prompts Tested:**
- *heartless*
- *I Wonder*
- *Runaway*

**Key Features:**
- Uses HuggingFace's Transformers library
- Fine-tunes GPT-2 on artist-specific lyric files (e.g., `Kanye_West.txt`)
- Capable of generating diverse and stylistically consistent lyrics
- Fully scriptable for training, saving, and inference

**Tools & Libraries:**
- Python 3.8+
- PyTorch
- HuggingFace Transformers
- Kaggle API
- NumPy, Pandas

📁 More details available in `GPT2/README.md`

---

## ⚙️ Setup Instructions

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/deep-learning-assignment-2.git
   cd deep-learning-assignment-2
