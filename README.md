# 📰 Masterclass NLP – Fake News Detection with AI  

## 🎯 Objective  
This masterclass introduces **Natural Language Processing (NLP)** and its application in **fake news detection**. Participants will learn how to analyze textual data, extract relevant features, and build a classification model to differentiate between real and fake news articles.  

## 📂 Repository Structure  

This repository contains all the necessary resources to **preprocess text data, train a classification model, and deploy it using Streamlit**.  

```
masterclass_nlp/
│── lectures/                   # Lecture materials and notebooks
│   ├── notebooks/             # Jupyter Notebooks for step-by-step analysis
│   ├── data/                  # Dataset for lectures
│   ├── streamlit/             # Streamlit-based examples and exercises
│── project/                    # Hands-on project for participants
│   ├── data/                  # Dataset for project
│   ├── mission.ipynb          # Jupyter Notebook with project details
│── README.md                   # Project documentation
```

---

## 🗓 Masterclass Schedule  

### 🕙 **Morning Session: Introduction to NLP & Basic Modeling**  
- **Overview of NLP for Fake News Detection** 🐝  
  - Evolution from traditional models to modern LLMs  
  - Challenges in NLP (bias, misinformation, interpretability)  

- **Text Preprocessing with SpaCy** ✍️  
  - Tokenization, lemmatization, stopword removal  
  - Cleaning and structuring text data  

- **Feature Extraction and Simple Classification** 📊  
  - Text representation methods (TF-IDF, embeddings)  
  - Training a simple logistic regression classifier  

- **Introduction to Streamlit** 🖥️  
  - Developing a basic app to visualize text classification results  

---

### 🕑 **Afternoon Session: Group Project – Fake News Detection**  
- **Dataset Exploration** 📰 (Fake and real news articles from U.S. elections 2016)  
- **Advanced Text Preprocessing and Feature Engineering** 🔍  
- **Training and Evaluating a Classification Model** 🤖  
- **Building an Interactive Streamlit App** 🏰  
- **Presenting Results and Discussion** 🎤  

---

## 📂 Dataset Information for the project
- **Source**: Fake and Real News Dataset from Kaggle  
- **Content**: Articles labeled as "Real" or "Fake," including title, body text, subject, and publication date.  

## 🚀 Technologies Used  
- **Python** 🐍 (pandas, NumPy, Scikit-learn)  
- **SpaCy** for text preprocessing  
- **Streamlit** for app development  
- **Matplotlib / Seaborn** for visualization  

## 👅 Installation and Execution  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/sbendimerad/masterclass_nlp.git
cd masterclass_nlp
```

### **2️⃣ Set Up the Environment**  
```bash
conda env create -f environment.yml
conda activate masterclass_nlp
```

### **3️⃣ Run the Streamlit App**  
```bash
streamlit run app.py
```

## 🤝 Contribution and Contact  
Feel free to ask questions and suggest improvements!  

