# 📌 Mini Project 2: Text Preprocessing & Sentiment Classification with NLP

---

##  Overview  
This project transforms **noisy raw text**—like product reviews or feedback containing stopwords, special characters, and inconsistent word forms—into clean, machine-readable features using NLP techniques. It then uses these features to train classification models (Random Forest, Naive Bayes) for **sentiment analysis** (Positive, Negative, Neutral).

---

##  Project Structure  
├── Product_Reviews.csv # Dataset file: reviews + sentiments
├── miniproject2.ipynb # Jupyter Notebook (compatible with Google Colab)
└── README.md # Project documentation


---

##  Objectives  
- Clean and preprocess text: lowercase, remove noise, stopword removal, stemming  
- Convert text to numeric form using:  
  - Bag of Words (BoW)  
  - TF-IDF  
  - N-Grams  
- Train and compare models:  
  - Random Forest  
  - Multinomial Naive Bayes  
- Evaluate using accuracy, F1-score, confusion matrix, and classification report  

---

##  Dataset  
**File:** `Product_Reviews.csv`  

**Columns:**  
- **Product ID** — Unique identifier  
- **Product Review** — Customer feedback text  
- **Sentiment** — POSITIVE / NEGATIVE / NEUTRAL  

---

##  Technologies & Libraries  
- **Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy` — Data handling  
  - `nltk` — Text preprocessing (stopwords, stemming)  
  - `scikit-learn` — Vectorization & model building  
  - `matplotlib`, `seaborn` — Data visualization  

---

### ▶️ Run Locally

##  Results Highlights  
- **Top Model:** Naive Bayes with Bag of Words  
- **Accuracy:** ~82%  
- **Macro F1-Score:** ~0.56  
- **Observations:** Positive reviews were classified most accurately, while Neutral and Negative reviews posed more challenges.
