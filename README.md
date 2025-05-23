# 📩 SMS Spam Classifier

An intelligent machine learning-based SMS Spam Classifier that automatically detects whether a given SMS message is **Spam** or **Ham (Not Spam)**. This project demonstrates text preprocessing, feature engineering using TF-IDF, and model training using the Naive Bayes algorithm.

---

## 📌 Objective

The primary goal of this project is to build a system that classifies SMS messages as either spam or ham, helping reduce the risk of phishing, scams, and unwanted promotional messages.

---

## 📊 Dataset

- **Name**: SMSSpamCollection
- **Source**: UCI Machine Learning Repository
- **Samples**: 5,574 SMS messages labeled as "spam" or "ham"
- **Attributes**:
  - `label`: Class label (spam/ham)
  - `message`: The actual SMS text

---

## 🧠 Model Used

- **Algorithm**: Multinomial Naive Bayes
- **Why?**:
  - Efficient for text classification problems
  - Works well with TF-IDF feature representations
  - Fast training and prediction time

---

## ⚙️ Project Workflow

1. **Text Preprocessing**:
   - Lowercasing
   - Removing punctuation
   - Removing stopwords
   - Stemming

2. **Feature Extraction**:
   - TF-IDF Vectorization

3. **Model Training**:
   - Split into Train/Test sets
   - Fit Multinomial Naive Bayes

4. **Evaluation**:
   - Accuracy, Precision, Recall, F1-score

---

## 📈 Performance Metrics

| Metric     | Score    |
|------------|----------|
| Accuracy   | ~97%     |
| Precision  | High     |
| Recall     | High     |
| F1-Score   | High     |

> Note: These metrics may vary slightly depending on train-test split and random seed.

---

## 🧩 Challenges & Learnings

### Challenges:
- Handling noisy text data
- Dealing with class imbalance
- Choosing the right vectorization method
- Avoiding overfitting

### Learnings:
- Basics of NLP and text preprocessing
- Implementation of Naive Bayes for text
- Model evaluation on imbalanced data
- Pipeline creation for text-based ML systems

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/campusx-official/sms-spam-classifier.git
cd sms-spam-classifier

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook sms-spam-detection.ipynb
```

---

## 🛠️ Requirements

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Jupyter Notebook

---

## 📬 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ✨ Acknowledgments

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)
- [CampusX YouTube Channel](https://www.youtube.com/c/CampusX)

---
#   S M S - s p a m - c l a s s i f i e r  
 