# 🍽️ Restaurant Review Sentiment Analysis  
### 🧠 A Natural Language Processing Project using Python & Google Colab

---

## 📘 Project Overview

This project focuses on analyzing restaurant customer reviews to determine the **sentiment** (positive or negative) using **Natural Language Processing (NLP)** techniques. The goal is to help restaurant owners understand customer feedback at scale and make **data-driven decisions** to improve their service and offerings.

---

## 🧰 Tools & Technologies Used

🔹 **Google Colab (Jupyter Notebook)**  
🔹 **Python**  
🔹 **Pandas & NumPy**  
🔹 **NLTK / spaCy / re (Text Processing)**  
🔹 **Scikit-learn**  
🔹 **Matplotlib & Seaborn (for visualizations)**  
🔹 **Logistic Regression / Naive Bayes / SVM (ML Models)**  

---

## 📂 Project Structure
Restaurant-Review-Sentiment-Analysis/
│
├── Web_analytics_Project.ipynb # Main notebook (NLP sentiment analysis)
├── README.md # Project documentation
├── data/ # CSV or raw review dataset
└── images/ # Model results or wordclouds


---

## 🧾 Dataset Overview

The dataset consists of restaurant reviews with two main columns:

- 📝 `Review`: Text data containing the customer's written feedback  
- 🟢 `Liked` (or `Sentiment`): Binary label indicating sentiment  
  - `1` = Positive  
  - `0` = Negative  

---

## ⚙️ Project Workflow

1. **Data Preprocessing**  
   - Lowercasing, punctuation removal, stopword removal, stemming/lemmatization  
2. **Text Vectorization**  
   - Bag of Words / TF-IDF  
3. **Model Training**  
   - Logistic Regression, Naive Bayes, SVM, or other classifiers  
4. **Evaluation Metrics**  
   - Accuracy, Confusion Matrix, Precision, Recall, F1-score  
5. **Visualization**  
   - WordCloud, class distribution, model performance plots

---

## 📊 Sample Visual Output of first 200 reviews from total reviews

## 🔍 Confusion Matrix
<p align="center">
  <img src="C:\Users\amytv\OneDrive\Pictures\Screenshots\Screenshot 2025-06-02 160951.png" width="700"/>
</p>
---

## 💡 Key Insights

✅ Majority of negative reviews use specific keywords (e.g., *slow*, *rude*, *cold*)  
✅ Positive sentiment strongly correlates with words like *delicious*, *friendly*, *quick*  
✅ Logistic Regression and Naive Bayes perform well for binary text classification  
✅ Model accuracy reaches **85–90%** depending on the algorithm and preprocessing

---

## 🎯 Objectives

🎯 Automate sentiment classification of restaurant reviews  
🎯 Extract meaningful patterns from large-scale unstructured text data  
🎯 Evaluate model performance for real-world feedback analysis  
🎯 Enable smarter decisions using customer voice data  

---

## 🛠️ How to Run

1. Open the notebook using [Google Colab](https://colab.research.google.com/).  
2. Upload your review dataset or use the included sample.  
3. Run cells sequentially to process text and train the model.  
4. Analyze model outputs and insights in real time.

---

## 🚀 Future Enhancements

🚧 Deploy as a live web app using **Streamlit** or **Flask**  
📈 Add multi-class classification (e.g., neutral sentiment)  
🧠 Use **transformer-based models** (e.g., BERT) for better accuracy  
🌐 Connect with **Google Reviews API** or other live review sources

---

## 👨‍💻 Author

**Name**: *[AMIT VERMA]*  
**Course**: BBA (Analytics & Big Data), UPES  
**Email**: [amytverma20@gmail.com]  
**LinkedIn**:[https://www.linkedin.com/in/amitverma20/]

---

## 📝 License

This project is developed for academic purposes under the Big Data Analytics curriculum at UPES.

---
