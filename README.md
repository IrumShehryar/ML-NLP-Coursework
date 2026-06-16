# ML-NLP-Coursework

📚 **My learning repository for Machine Learning and Natural Language Processing coursework**

This is an **ongoing collection** of Google Colab notebooks and projects that I'm working through as I progress through ML and NLP courses. Each notebook represents hands-on practice and experimentation as I learn new concepts.

---

## 📂 Repository Structure

```
ML-NLP-Coursework/
├── machine-learning/
│   ├── Project08_Regularization_Ridge_Lasso_ENet.ipynb
│   ├── Project09_GridSearchCV.ipynb
│   ├── classification/
│   │   └── Project_01_Getting_Class_Probabilities.ipynb
│   ├── weekly-notebooks/
│   └── README.md
├── ml/
│   ├── 03-tuning-and-validation/
│   │   ├── Project08_Regularization_Ridge_Lasso_ENet.ipynb
│   │   └── Project09_GridSearchCV.ipynb
│   └── 04-classification-models/
│       └── Project_01_Getting_Class_Probabilities.ipynb
├── nlp/
│   └── README.md
└── README.md
```

---

## 🎯 What's Inside

### 📊 Regression & Regularization
**`Project08_Regularization_Ridge_Lasso_ENet.ipynb`**
- Learning regularization techniques to prevent overfitting
- Implementing Ridge Regression (L2 penalty)
- Implementing Lasso Regression (L1 penalty)
- Understanding Elastic Net (L1 + L2 combination)
- Comparing model performance with different regularization strengths

### 🔍 Hyperparameter Tuning
**`Project09_GridSearchCV.ipynb`**
- Using GridSearchCV for systematic hyperparameter search
- Cross-validation techniques
- Finding optimal parameters for Ridge Regression
- Evaluating model performance on train/test data

### 🏥 Classification & Probability
**`classification/Project_01_Getting_Class_Probabilities.ipynb`**
- Introduction to Logistic Regression
- Binary classification with tumor size dataset
- Understanding class probabilities
- Making predictions on new data

---

## 🛠️ Tools & Libraries Used

```python
import numpy as np              # Numerical computing
import pandas as pd             # Data manipulation
import matplotlib.pyplot as plt # Visualization
from sklearn.linear_model import Ridge, Lasso, ElasticNet, LogisticRegression
from sklearn.model_selection import train_test_split, GridSearchCV, cross_val_score
import sklearn.metrics as metrics
```

---

## 💡 Key Concepts I'm Learning

✅ **Regression Analysis**
- Model fitting and evaluation
- Regularization techniques (L1, L2)
- Hyperparameter tuning
- Cross-validation strategies

✅ **Classification**
- Logistic Regression
- Probability estimation
- Binary classification
- Model metrics (accuracy, precision, recall)

✅ **Model Optimization**
- GridSearchCV for hyperparameter search
- Cross-validation for robust evaluation
- Training vs. test performance analysis

✅ **Data Handling**
- Loading and exploring datasets
- Train-test splitting
- Feature scaling and normalization
- Data preparation for modeling

---

## 🚀 How to Use These Notebooks

### Option 1: Google Colab (Recommended - These are Colab Notebooks!)
1. Go to [Google Colab](https://colab.research.google.com)
2. Select "GitHub" tab
3. Search for my repo: `IrumShehryar/ML-NLP-Coursework`
4. Click on any notebook to open and run it
5. These notebooks are designed to run in Google Colab environment

### Option 2: Local Machine
```bash
# Clone the repository
git clone https://github.com/IrumShehryar/ML-NLP-Coursework.git
cd ML-NLP-Coursework

# Install dependencies
pip install numpy pandas scikit-learn matplotlib

# Start Jupyter
jupyter notebook
```

---

## 📖 Learning Path (My Journey So Far)

1. **Start Here**: `classification/Project_01_Getting_Class_Probabilities.ipynb`
   - Understand basics of classification
   - Learn about probability predictions

2. **Then Explore**: `Project08_Regularization_Ridge_Lasso_ENet.ipynb`
   - Deep dive into regression
   - Learn different regularization approaches

3. **Master**: `Project09_GridSearchCV.ipynb`
   - Optimize models systematically
   - Practice hyperparameter tuning

4. **Coming Next**: More advanced topics as I progress through the course...

---

## 📚 Datasets Used

- **Regression_Data.csv**: Simple regression dataset (30 samples, 2 columns)
  - Independent variable: continuous values
  - Dependent variable: continuous output
  
- **Synthetic Data**: Generated within notebooks
  - Tumor size classification dataset
  - Binary outcomes (cancer/no cancer)

---

## 📊 Sample Projects Overview

### Ridge, Lasso & Elastic Net
```
Input: Regression data with independent and dependent variables
Process: 
  1. Load and explore data
  2. Split into train/test sets
  3. Train multiple regularization models
  4. Compare performance
Output: Visualizations comparing model performance
```

### GridSearchCV
```
Input: Regression data
Process:
  1. Define parameter grid
  2. Create Ridge model
  3. GridSearchCV for best parameters
  4. Evaluate on test set
Output: Best hyperparameters and model metrics
```

### Logistic Regression
```
Input: Tumor size and cancer labels
Process:
  1. Reshape features for sklearn
  2. Train LogisticRegression model
  3. Get probability predictions
  4. Make class predictions
Output: Probability scores and class labels
```

---

## 🎓 Course Topics Covered

**Currently Learning:**
- ✅ Supervised Learning (Regression & Classification)
- ✅ Regularization Techniques
- ✅ Hyperparameter Optimization
- ✅ Cross-Validation
- ✅ Model Evaluation Metrics

**Coming Up (As Course Progresses):**
- 🔜 Feature Engineering
- 🔜 Unsupervised Learning
- 🔜 Natural Language Processing
- 🔜 Deep Learning
- 🔜 More advanced ML techniques...

---

## 📝 About These Notebooks

These are **Colab-based learning notebooks** where I:
- 🔬 **Experiment** with new ML concepts as I learn them
- 📖 **Practice** implementing algorithms
- 🎯 **Understand** how different models work
- 📊 **Visualize** results and compare approaches
- 💬 **Document** my learning with comments and explanations

Each notebook includes:
- Clear explanations of concepts
- Step-by-step implementation
- Data exploration and visualization
- Performance comparisons
- Comments explaining the "why" behind the code

---

## 🔄 How This Repository Grows

This is an **active, ongoing repository**. As I progress through my ML and NLP courses:

- ✅ New projects and notebooks will be added regularly
- ✅ Each topic will have dedicated notebooks and folders
- ✅ More advanced techniques will be explored
- ✅ Real-world projects and datasets will be incorporated
- ✅ NLP coursework will be added as it progresses

**Check back regularly for updates!** 📈

---

## 💡 Tips for Using These Notebooks

- **Run cells sequentially**: Each notebook builds on previous cells
- **Experiment**: Try changing parameters and see how models respond
- **Visualize**: Look at plots to understand model behavior
- **Compare**: Use different models on same data to see differences
- **Take notes**: Add your own comments and observations
- **Modify code**: Make changes to solidify your understanding

---

## ✨ What I'm Currently Working On

- [ ] Completing more regression and classification projects
- [ ] Starting NLP course materials
- [ ] Exploring more advanced classification algorithms
- [ ] Learning unsupervised learning techniques
- [ ] Building real-world practice projects
- [ ] Adding model interpretation and explainability

**Next milestones**: Feature engineering, ensemble methods, introduction to NLP

---

## 📚 Resources & References

- Scikit-learn Documentation: https://scikit-learn.org/
- Pandas Documentation: https://pandas.pydata.org/
- NumPy Documentation: https://numpy.org/
- Google Colab: https://colab.research.google.com
- Kaggle: https://www.kaggle.com (datasets and competitions)

---

## 💬 About This Repository

This is my personal learning repository created while working through ML and NLP coursework. It serves as:
- 📓 A record of my learning journey
- 🎯 A collection of practice projects
- 📚 A reference for concepts and implementations
- 🔄 A growing resource that updates as I learn

Feel free to explore these notebooks, learn from them, or use them as a reference for your own learning journey!

---

**Last Updated**: June 2026  
**Status**: 🔄 **Actively Learning & Adding Content**  
**Current Focus**: Regression, Classification, Hyperparameter Tuning  
**Platform**: Google Colab + Local Jupyter  

*This repository will continue to grow and evolve as my coursework progresses. Stay tuned for more advanced topics! 🚀*
