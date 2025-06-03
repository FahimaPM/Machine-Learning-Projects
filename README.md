# 📧 Spam Email Detection using Machine Learning

## 📝 Project Overview

This project demonstrates a **binary classification model** to detect spam emails using natural language processing (NLP) techniques and machine learning. Given an email dataset labeled as **spam** or **ham**, we build a logistic regression classifier to distinguish between the two classes.

---

## 📂 Files

- `spam_projct.ipynb`: Jupyter Notebook containing all code — data preprocessing, model training, evaluation, and visualization.
- `email.csv`: Dataset containing labeled email messages.

---

## ⚙️ Technologies & Libraries Used

- Python (v3.x)
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib / Seaborn (optional, for visualization)

---

## 🔍 Dataset Description

The `email.csv` file contains two main columns:
- `Category`: Label for each email (`spam` or `ham`)
- `Message`: The actual content of the email

---

## 🧠 Model Workflow

1. **Data Loading**  
   Load and inspect the dataset for structure and balance.

2. **Data Cleaning & Preprocessing**
   - Convert labels (`spam`, `ham`) to numerical format (1, 0)
   - Lowercasing, punctuation removal, stopword filtering
   - Tokenization and lemmatization using **NLTK**

3. **Feature Extraction**
   - TF-IDF vectorization using `TfidfVectorizer` for converting text to numerical features

4. **Model Training**
   - Logistic Regression model trained on processed data

5. **Evaluation**
   - Evaluated the accuracy of the model on both the training dataset and the testing dataset to assess performance and generalization
   - Confusion matrix and classification report

---

## ✅ Results

- **Accuracy Achieved**: ~94–96% (based on train-test split)
- **Insights**:
  - TF-IDF is effective in capturing keyword significance.
  - Logistic regression works well for baseline spam detection.

---

## 🚀 How to Run

1. Clone this repository or download the files  
2. Ensure dependencies are installed:
   ```bash
   pip install pandas numpy scikit-learn nltk
   ```
3. Open `spam_projct.ipynb` in Jupyter Notebook
4. Run the cells sequentially to execute the workflow

---

## 🧑‍💻 Author

**Fahima P.M**  
Contact: fahima9042@gmail.com  

