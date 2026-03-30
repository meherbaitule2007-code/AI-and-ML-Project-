# 🤖 ML-Based Sentiment Analyzer (Improved Version)

## 📌 Overview
This project is a **machine learning-based sentiment analyzer** developed for the **Fundamentals of AI** practical.

It classifies sentences into three categories:
- ✅ Positive  
- ❌ Negative  
- ➖ Neutral  

### 🔥 Improvements in this Version
- Model accuracy calculation  
- Probability scores for predictions  
- Loop-based user input  
- Flowchart & architecture diagram  
- Clean Jupyter Notebook implementation  

---

## 🚀 Features
✔️ Machine learning–based sentiment classification  
✔️ Uses **CountVectorizer (Bag of Words)**  
✔️ Uses **Multinomial Naive Bayes**  
✔️ Displays **probabilities for each class**  
✔️ Evaluates **model accuracy**  
✔️ Simple and easy logic (perfect for viva/exams)  

---

## 📊 Dataset
Custom dataset containing **15 sentences**:
- 5 Positive  
- 5 Negative  
- 5 Neutral  

All sentences are **manually labeled**.

---

## 🔄 Flow Diagram
┌────────────────────────┐
│ User Input │
│ (Sentence/Statement) │
└────────────┬───────────┘
│
▼
┌────────────────────────┐
│ Text Preprocessing │
│ - Lowercasing │
│ - Tokenization │
└────────────┬───────────┘
│
▼
┌────────────────────────┐
│ Feature Extraction │
│ CountVectorizer │
│ (Bag of Words Model) │
└────────────┬───────────┘
│
▼
┌─────────────────────────┐
│ ML Model Training │
│ Multinomial Naive Bayes │
└────────────┬────────────┘
│
▼
┌─────────────────────────┐
│ Prediction │
│ - Sentiment Label │
│ - Class Probabilities │
└────────────┬────────────┘
│
▼
┌──────────────────────────┐
│ Output │
│ Positive/Negative/Neutral│
│ + Probabilities │
└──────────────────────────┘

---

## 📈 Model Accuracy
A small test dataset is used to evaluate performance:

> ⚠️ Note: Accuracy may vary slightly depending on dataset variations.

---

## 💡 Example Output
Enter a sentence: I am happy today

Predicted Sentiment: Positive

Class Probabilities:
Negative : 0.05
Neutral : 0.10
Positive : 0.85
---

## ⚙️ How to Run

### 1️⃣ Install Dependencies
```bash
pip install scikit-learn

python sentiment_analyzer.py

📁 File Structure
ai-sentiment-analyzer/
│
├── sentiment_analyzer.ipynb
├── sentiment_analyzer.py
├── requirements.txt
└── README.md

🖼️ Output Screenshots


<img width="449" height="433" alt="Output" src="https://github.com/user-attachments/assets/7b416fba-b090-4fd5-bea3-8e55db10af66" />


