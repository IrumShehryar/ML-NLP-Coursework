# ML-NLP-Coursework

📚 Hands-on Jupyter notebooks for core Machine Learning and Natural Language Processing coursework. Notebooks are concise, practical, and runnable in Jupyter or Google Colab — focused on examples and short exercises for learning and revision.

## Top-level structure
- `ml/` — Machine Learning notebooks (01-data-preprocessing → 12-unsupervised-learning). Covers preprocessing, regression, tuning & validation, classification, neural networks (CNN/RNN), generative models and unsupervised learning (PCA).
- `nlp/` — Natural Language Processing notebooks (01-text-preprocessing → 08-Time-series-transformer). Covers tokenization, vectorization, classical models, neural approaches, transfer learning and transformer-based notebooks.

## Quick highlights

### ML — Supervised learning
- Regression: linear, polynomial, and multiple regression examples (ml/02-regression-models).
- Classification: classical classifiers and model pipelines (ml/04-classification-models) including KNN, SVM, decision trees, random forest and boosting.
- Neural networks: feedforward, CNNs (ml/08-CNN) for images, RNNs/LSTMs (ml/09-RNN) for sequences — includes training and evaluation examples.
- Model tuning & validation: cross-validation and hyperparameter search (ml/03-tuning-and-validation).

### ML — Unsupervised & generative
- Dimensionality reduction & PCA projects (ml/12-unsupervised-learning/PCA/Project_01 → Project_06).
- Autoencoders (ml/10-AutoEncoders) and GAN experiments (ml/11-Geneartive-Adversial-Networks) for representation learning and generation.

### NLP
**Preprocessing**
- Tokenization, cleaning, stopwords, stemming & lemmatization (nlp/01-text-preprocessing).

**Vectorization & classical models**
- Count/TF‑IDF, word indices, co-occurrence intuition and topic/sentiment examples (nlp/02-text-vectorization, nlp/03-classical-nlp-models).

**Neural & Transformers**
- Embeddings, pretrained word vectors (gensim), RNN/BiLSTM experiments (nlp/04-neural-network, nlp/07-BiLSTM).
- Transfer learning and fine-tuning transformer notebooks (nlp/05-transfer-learning, nlp/06-fine-tuning-transformer, nlp/08-Time-series-transformer).

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

**Status:** ✅ Coursework completed — Last updated: 2026-09-09
