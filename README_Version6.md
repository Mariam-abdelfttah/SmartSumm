# 🧾 SmartSumm: Abstractive Summarization with Transformers and TextRank

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/License-MIT-green">
  <img src="https://img.shields.io/badge/Hugging%20Face-Transformers-yellow?logo=huggingface">
  <img src="https://img.shields.io/badge/Status-Active-success">
</div>

---

## 🚀 Project Overview

**SmartSumm** is a research project comparing the performance of state-of-the-art abstractive summarization models (**BART**, **T5**) with the traditional extractive method **TextRank**. Using the XSum news dataset, the project evaluates the accuracy and efficiency of modern models for automatic text summarization.

---

## 🎯 Objective

Summarizing long content is crucial in domains such as news, medicine, and education. This project addresses the question:

> "Do Transformer-based models truly outperform traditional approaches for text summarization?"

---

## ✨ Features

- ⚡️ Utilizes pre-trained models from Hugging Face: `facebook/bart-large-xsum`, `t5-base`
- 📰 Summarizes 50 real news articles
- 📊 Compares performance using ROUGE scores
- 📈 Visualizes differences between models
- 🗂️ Saves all results in a structured CSV file

---

## 🛠️ Tech Stack

- Python 3.8+
- Hugging Face Transformers
- Datasets (XSum)
- Sumy, NLTK
- Matplotlib, pandas

---

## 🚦 Quick Start

1. Make sure you have Python and Jupyter Notebook installed, or use Google Colab.
2. Install the required libraries:
   ```bash
   pip install transformers datasets rouge-score sumy nltk matplotlib pandas
   ```
3. Download the `xsum.csv` data file and place it in the correct directory.
4. Run the script or the provided notebook.

---

## 📂 Project Structure

```
SmartSumm/
├── src/
│   └── summarizer.py
├── notebooks/
│   └── SmartSumm_Comparison.ipynb
├── data/
│   └── xsum.csv
├── results/
│   └── summaries.csv
├── README.md
```

---

## 📊 Results

| Model     | ROUGE-1 | ROUGE-2 | ROUGE-L |
|-----------|---------|---------|---------|
| **BART**      | 0.4821  | 0.2541  | 0.4075  |
| **T5**        | 0.1975  | 0.0366  | 0.1425  |
| **TextRank**  | 0.1633  | 0.0276  | 0.1107  |

> **BART significantly outperforms both T5 and TextRank across all ROUGE metrics, demonstrating the power of transformer-based abstractive summarization on news data.**

---

## 🤝 Contribution

This project is open source! If you have suggestions or enhancements, feel free to open a Pull Request or Issue.

---

## 📬 Contact

For questions or collaboration:
-Mariam [GitHub](https://github.com/Mariam-abdelfttah)
- Omnia [GitHub](https://github.com/Omnia-adel1)
  
-Mariam Elrafei — Lead Developer & Researcher
Worked on model implementation, data preprocessing, and evaluation metrics.

-Omnia Adel — Data Engineer & Analyst
Handled dataset preparation, performance visualization, and results analysis.



---

<div align="center">
  <b>Thank you for your interest in the SmartSumm project ⭐</b>
</div>
