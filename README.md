## 📰 Fake News Detection using NLP

This project focuses on detecting fake news articles by applying Natural Language Processing (NLP) and machine learning. The goal is to classify whether a given news article is **real** or **fake** based on its text content.

### 📂 Dataset
- Dataset of labeled news articles (real/fake).
- Includes article headlines, authors, and main text.

### 🔍 Methodology
1. **Text Preprocessing**:
   - Cleaning raw text data (lowercasing, stopword removal).
   - Tokenization and lemmatization.
2. **Feature Extraction**:
   - TF-IDF vectorization for text representation.
3. **Model Training**:
   - Logistic Regression, Naive Bayes, and Random Forest classifiers.
4. **Evaluation**:
   - Accuracy, precision, recall, F1-score.
   - Confusion matrix for classification results.

### 🛠️ Tech Stack
- Python (Pandas, NumPy, Scikit-learn)
- NLTK/SpaCy for NLP preprocessing
- Matplotlib & Seaborn for visualization

### 🚀 How to Run
1. Clone the repo
2. Install requirements: `pip install -r requirements.txt`
3. Run the notebook to train models and evaluate results
