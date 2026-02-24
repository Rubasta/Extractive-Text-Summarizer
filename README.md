# 🧠 Extractive Text Summarization using TF-IDF & PageRank

An unsupervised Machine Learning based Extractive Text Summarizer built using Python, NLP, TF-IDF vectorization and the PageRank algorithm.

This project automatically generates a concise summary from a long paragraph by selecting the most important sentences.

---

## 🚀 Project Overview

Reading long articles, blogs, or reports can be time-consuming.  
This project builds a lightweight ML-based system that:

- Takes user input text
- Analyzes sentence importance
- Ranks sentences using graph-based scoring
- Generates a short, meaningful summary

This is an **Extractive Summarization** model, meaning it selects important sentences from the original text instead of generating new ones.

---

## 🏗️ How It Works

The system follows these steps:

1. **Sentence Tokenization**  
   Breaks the paragraph into individual sentences.

2. **Text Preprocessing**
   - Lowercasing
   - Removing punctuation
   - Removing stopwords

3. **TF-IDF Vectorization**
   Converts each sentence into numerical vectors based on word importance.

4. **Similarity Matrix**
   Computes similarity between sentences using cosine similarity.

5. **Graph Construction**
   Builds a graph where:
   - Each sentence is a node
   - Similarity score acts as edge weight

6. **PageRank Algorithm**
   Applies PageRank to rank sentences by importance.

7. **Summary Generation**
   Selects top-ranked sentences while preserving original order.

---

## 📊 Technologies Used

- Python
- NLTK
- Scikit-learn
- NetworkX
- Google Colab

---

## 🧠 Machine Learning Concepts Used

- Unsupervised Learning
- TF-IDF (Term Frequency – Inverse Document Frequency)
- Cosine Similarity
- Graph-Based Ranking
- PageRank Algorithm
- Natural Language Processing (NLP)

---

## 📌 Installation

Install required libraries:

```bash
pip install nltk networkx scikit-learn
```

---

## ▶️ How to Run

1. Open Google Colab
2. Install required libraries
3. Copy the main Python code
4. Run the notebook
5. Enter your paragraph
6. Enter desired number of sentences for summary
7. Get generated summary output

---

## 💡 Example Input

```
Artificial Intelligence is rapidly transforming industries across the world.
Machine learning, a subset of AI, allows computers to learn from data.
Deep learning enhances AI capabilities using neural networks.
AI systems require large amounts of data to function effectively.
```

### Example Output (2 sentences)

```
Machine learning, a subset of AI, allows computers to learn from data.
AI systems require large amounts of data to function effectively.
```

---

## 🎯 Features

- Dynamic user input
- Adjustable summary length
- Preserves sentence order
- Lightweight and fast
- No pretrained models required
- Fully explainable ML pipeline

---

## 📈 Advantages

- Works without large datasets
- No GPU required
- Easy to understand and extend
- Suitable for academic and ML learning purposes

---

## ⚠️ Limitations

- Does not generate new sentences (Extractive only)
- Does not understand deep semantic meaning
- Performance depends on text structure

---

## 🔮 Future Improvements

- Add position-based sentence weighting
- Add redundancy reduction
- Compare with Transformer-based models
- Add ROUGE score evaluation
- Deploy as a web app using Flask or Streamlit

---

## 👨‍💻 Author

Sagnik Basu  
Computer Science Enthusiast | Machine Learning Learner

---

## ⭐ If You Like This Project

Give it a star on GitHub and feel free to contribute!
