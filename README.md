# SMS Spam Detection: Evolution from ML to Transformers

This repository demonstrates the evolution of Natural Language Processing (NLP) techniques for SMS Spam detection. It compares traditional Machine Learning approaches with state-of-the-art Deep Learning models.

## 🚀 Project Overview
The goal is to accurately classify SMS messages into **Ham** (legitimate) or **Spam**. The project is divided into two main phases:

### Phase 1: Classical Machine Learning
- **Feature Extraction:** TF-IDF Vectorization.
- **Algorithms:** Logistic Regression, Multinomial Naive Bayes, and **LinearSVC**.
- **Results:** Achieved a high accuracy of **98.9%** using LinearSVC.
- **Tools:** `scikit-learn`, `pandas`, `numpy`.

### Phase 2: Modern Deep Learning (Transformers)
- **Model:** **DistilBERT** (a light and fast version of BERT).
- **Technique:** Using Hugging Face `pipelines` for contextual understanding.
- **Advantages:** Unlike traditional methods, BERT understands the context and semantics of words, making it more robust against unseen data and tricky spam patterns.
- **Tools:** `transformers` library, `PyTorch`.

## 📁 Repository Structure
```text
├── data/
│   └── smsspamcollection.tsv   # Original dataset
├── notebooks/
│   ├── 01_Classical_ML.ipynb   # Initial ML experiments
│   └── 02_BERT_Approach.ipynb  # Advanced Transformer implementation
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```
📊 Dataset
The project uses the SMS Spam Collection Dataset, which contains 5,572 messages labeled as ham or spam.

🛠️ How to Run
Clone the repository:

Bash
git clone [https://github.com/YourUsername/Spam-Detection-Evolution.git](https://github.com/YourUsername/Spam-Detection-Evolution.git)
Install dependencies:

Bash
pip install -r requirements.txt
Open the notebooks in Google Colab or Jupyter Notebook.

💡 Key Learnings
Traditional ML models are extremely fast and efficient for specific datasets.

Transformers (BERT) provide deeper linguistic understanding and generalize better to real-world scenarios.
