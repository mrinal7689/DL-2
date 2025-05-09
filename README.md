
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

**Performance:**
- The model achieves a validation accuracy of over 85% using the LSTM cell architecture.
- Training time varies between 5–10 minutes on a standard GPU (Colab).
- The GRU-based model showed slightly faster convergence than vanilla RNN, while LSTM provided the best accuracy.
![Screenshot 2025-04-20 181939](https://github.com/user-attachments/assets/b6025553-99de-4cbf-bef5-ef196a7b1f33)



**Tools & Libraries:**
- Python 3.8+
- TensorFlow 2.x
- NumPy
  

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

**Performance:**
- Fine-tuning was done for 3 epochs with a batch size of 2.
- The model began generating stylistically accurate lyrics after just 1 epoch.
- Prompt-based generation produced unique, grammatically correct lines that resemble Kanye West's lyrical patterns.
- Generation temperature set to 0.9 for creative outputs with top_k = 50 and top_p = 0.95

![Screenshot_20-4-2025_182032_colab research google com](https://github.com/user-attachments/assets/47c119f9-f223-4ed8-9ead-4bac2e2df318)


**Tools & Libraries:**
- Python 3.8+
- PyTorch
- HuggingFace Transformers
- Kaggle API
- NumPy, Pandas



---


