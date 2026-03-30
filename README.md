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

🖼️ Screenshots

<img width="583" height="190" alt="17748720623622448888178424673819" src="https://github.com/user-attachments/assets/fbdfb727-e9ee-4d6a-8d4f-1b96dd6eecbb" />


<img width="583" height="190" alt="17748720840211358136578011962524" src="https://github.com/user-attachments/assets/598d42c9-7ebf-4a56-a84b-89c54efe774a" />


<img width="583" height="190" alt="1774872103234171490500440613108" src="https://github.com/user-attachments/assets/4be7dfb0-7531-4a69-82a3-0438ae838113" />


