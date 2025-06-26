# Classification using Deep Learning
Predicting a given set of structured or unstructured data into classes.
Using different deep learning algorithms to map the input data to a specific category. The model learns from the given input data for training and assigns a class/label for the new data.


---

**Semantic Detection of SQL Injection Attacks Using Sentence Transformers**

---

### 📝 **Project Description:**

This project implements a natural language processing (NLP) pipeline to detect potential **SQL injection alerts** from system logs by comparing message content against known malicious query patterns. It utilizes **pre-trained Sentence-BERT (SBERT)** embeddings and **cosine similarity** to semantically compare log messages with suspicious query strings.

#### 🔍 Key Features:

* Loads and pre-processes log messages and alert labels.
* Embeds both log messages and attack patterns using `paraphrase-MiniLM-L6-v2`.
* Applies semantic similarity scoring to flag messages closely matching SQL injection patterns.
* Automatically computes a dynamic **threshold** based on similarity distribution to filter results.
* Evaluates model effectiveness using matching tags as ground truth.

#### 🚀 Tech Stack:

* Python 3.8+
* Libraries:
    * Pandas, NLTK
    * Sentence-BERT (from `sentence_transformers`)
    * Scikit-learn for splitting and metrics
    * JSON and CSV data integration

---
#### Use Cases

* Security Information and Event Management (SIEM)
* Intrusion Detection Systems (IDS)
* Automated log analysis and alert generation

