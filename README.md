### **README.md**

---

# **Flipkart Product Review Sentiment Analysis**

This project performs sentiment analysis on Flipkart product reviews, classifying them into **Happy**, **Ok**, and **Unhappy** categories based on user ratings.

---

## **Dataset**
- Source: [Flipkart Product Review Dataset (Kaggle)](https://www.kaggle.com/datasets/mansithummar67/flipkart-product-review-dataset).
- Key Features: 
  - `Summary` (short review text), `Rate` (1-5 ratings).

---

## **Requirements**
Install the required libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-plot scikit-learn wordcloud scipy kaggle
```

---

## **Steps**
1. **Data Preprocessing**:
- Clean missing values and preprocess review summaries.
2. **Feature Extraction**
   - Apply TF-IDF for word-level as well as char-level feature transformation.
3. **Model Training**
   - Train the models **LinearSVC** and **SGDClassifier** on the balanced class weights.
4. **Evaluation**
   - Accuracy, classification reports, and confusion matrices.

----

## **Results**
- Both train and test set achieved 92.3% accuracy.
- Confusion matrices will make explicit category-wise performance.

----

## **Usage
Run the Python script step-by-step to preprocess data, train models, and evaluate performance. 

---

## **Acknowledgments**
- Tools: Python, scikit-learn, matplotlib, seaborn.
