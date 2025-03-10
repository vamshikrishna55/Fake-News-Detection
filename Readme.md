# 📰 Fake News Detection using NLP & Machine Learning  

🚀 **Project Overview**  
This project aims to classify news articles as **Fake** or **Real** using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The model is trained on textual data and leverages **TF-IDF vectorization** with a **Linear SVC classifier** to make accurate predictions.

---

## 📂 Dataset  
- The dataset consists of labeled news articles categorized as **Fake (1)** or **Real (0)**.  
- The `text` column contains the news content, and the `label` column represents its authenticity.  

---

## 🛠️ Tech Stack  
✅ **Python** – Programming Language  
✅ **pandas, NumPy** – Data Handling  
✅ **nltk** – NLP Preprocessing  
✅ **matplotlib, seaborn** – Data Visualization  
✅ **scikit-learn** – Machine Learning  
✅ **SHAP** – Model Explainability  

---

## 📊 Exploratory Data Analysis (EDA)  
✔ **Word Cloud** visualization for Fake vs. Real news  
✔ **Text length distribution** to analyze word count patterns  
✔ **Class Distribution** to check data balance  

---

## 🔍 Model Training & Evaluation  
### **Text Preprocessing**  
- Tokenization  
- Stopword Removal  
- Lemmatization  
- **TF-IDF Vectorization** to convert text into numerical format  

### **Model Used:**  
- **Linear Support Vector Classifier (LinearSVC)**  
  - Efficient for text classification  
  - Works well with high-dimensional data  

### **Evaluation Metrics**  
✔ **Accuracy Score** – Measures overall performance  
✔ **Confusion Matrix** – Visualizes correct and incorrect classifications  
✔ **ROC Curve & AUC Score** – Analyzes model's discriminatory power  

---
## 📂 Dataset Download
Due to its large size, the dataset can be downloaded from [Google Drive](https://drive.google.com/file/d/1kUyHhhZEU998eWRo_yLoyKlNuhmTrDXB/view?usp=sharing).


## 📌 How to Run the Project  
1️⃣ **Clone the repository**  
```bash
git clone https://github.com/vamshikrishna55/Fake-News-Detection.git
cd Fake-News-Detection
