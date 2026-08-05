# ML-NLP-Coursework

📚 Hands-on Jupyter notebooks for core Machine Learning and Natural Language Processing coursework. Notebooks are concise, practical, and runnable in Jupyter or Google Colab — focused on examples, short explanations, and reproducible experiments.

## Top-level structure
- `ml/` — Machine Learning notebooks (01-data-preprocessing → 09-RNN). Covers preprocessing, regression, tuning & validation, classification, neural networks (CNN/RNN) and regularization techniques.
- `nlp/` — Natural Language Processing notebooks (01-text-preprocessing → 07-BiLSTM). Covers tokenization, vectorization, classical models, neural approaches, transfer learning and transformer fine-tuning.

## Quick highlights
- ml/: data cleaning, feature engineering, regression & classification examples, hyperparameter search, CNN/RNN experiments.
- ml/04-classification-models/ includes classical classifiers and subfolders (knn, svm, decision-tree, random-forest, boosting-methods, Naive_bayes).
- nlp/: tokenization, TF‑IDF and count vectorizers, topic modeling, sentiment/spam examples, transfer-learning and fine-tuning notebooks.

## Quick start
1. Clone the repo:

```bash
git clone https://github.com/IrumShehryar/ML-NLP-Coursework.git
cd ML-NLP-Coursework
```

2. Install common packages (adjust for notebooks that require TensorFlow/PyTorch or transformers):

```bash
pip install numpy pandas scikit-learn matplotlib nltk spacy jupyter
# for transformer notebooks:
pip install transformers torch  # or tensorflow
```

3. Open and run the notebooks in `ml/` or `nlp/` in Jupyter or Google Colab.

## Libraries commonly used
scikit-learn, pandas, numpy, matplotlib, seaborn, nltk, spacy, tensorflow / PyTorch, transformers

## Notes
- Each subfolder contains short, self-contained notebooks designed for learning and experimentation.
- See `ml/README.md` and `nlp/README.md` for area-specific summaries and quick run notes.

---

**Status:** 🔄 Coursework in progress — Last updated: 2026-08-05
