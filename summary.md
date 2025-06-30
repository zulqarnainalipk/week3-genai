
#  GenAI Learning Journey – 2-Week Summary

This document outlines my two-week deep dive into **Generative AI (GenAI)**, including a 5-day intensive course with Google, short courses from DeepLearning.ai, and a Kaggle hackathon on early sepsis prediction.

---

## ✅ Week 1: Google’s 5-Day Generative AI Intensive

### 📌 Overview
Completed a structured 5-day GenAI course hosted by Google, focusing on foundational principles, cutting-edge tools, and hands-on applications using large language models.

---

###  Daily Breakdown

#### **Day 1 – Foundational Models & Prompt Engineering**
- Studied the evolution of LLMs: `Transformers → Fine-tuning → Reasoning Models`
- Practiced foundational prompt engineering techniques

#### **Day 2 – Embeddings & Vector Stores**
- Learned how embeddings transform text into vector representations
- Explored vector databases for similarity search and retrieval

#### **Day 3 – Generative AI Agents**
- Built simple autonomous agents powered by LLMs
- Understood agent architecture, loops, and tool usage

#### **Day 4 – Domain-Specific LLMs**
- Studied task-specific models like `Med-PaLM` and `SecLM`
- Compared fine-tuned vs. instruction-tuned LLMs

#### **Day 5 – MLOps for Generative AI**
- Applied MLOps principles to GenAI pipelines
- Used Google Cloud’s `Vertex AI` for deployment and monitoring

---

###  Key Concepts Mastered

- Transformer-based LLM Architecture  
- Prompt Engineering (zero-shot, few-shot)  
- Embeddings & Vector Databases  
- Retrieval-Augmented Generation (RAG)  
- Agentic AI and Tool-using Agents  
- Instruction Tuning vs. Fine-tuning  
- MLOps in GenAI workflows  
- Inference Optimization and Scalability

---

###  Insight

> *Generative AI shifts the paradigm: we no longer build models from scratch but fine-tune powerful foundation models for specific tasks, enabling rapid, high-impact development.*

---

## 🧪 Kaggle Practice: *LLM - Detect AI Generated Text*

- Participated in a real-world text classification challenge
- Explored ML pipelines with `DistilBERT`, a lighter transformer variant
- Learned feature engineering, model training, and evaluation

#### 📚 Tools & Libraries:
```python
scikit-learn, pandas, numpy, matplotlib
````

#### 📊 Evaluation Metrics:

* Accuracy
* F1-Score
* ROC-AUC

---

## ✅ Week 2: Short Courses & Hackathon Presentation

### 📘 Courses Completed (DeepLearning.ai)

#### 1. ChatGPT Prompt Engineering for Developers

* Learned to create structured prompts using zero-shot & few-shot methods
* Explored `system messages` and prompt templates

#### 2. Building Applications with ChatGPT

* Built LLM workflows using OpenAI’s API
* Focused on multi-step reasoning and output formatting

#### 3. LangChain for LLM Application Development

* Developed LLM-powered apps using `chains`, `tools`, and `vector stores`
* Combined LLMs with external knowledge bases

---

##  Kaggle Hackathon Presentation: *PHEMS Pediatric Sepsis Prediction*

###  Overview

Delivered a project presentation based on the **PHEMS x TUM.ai Pediatric Sepsis Prediction Hackathon**, hosted on Kaggle. The competition focused on building ML models to predict **sepsis onset** in pediatric ICU patients using high-frequency physiological data.

* **Challenge**: Forecast early sepsis using time-series vitals
* **Data**: Multivariate clinical time-series (heart rate, temp, BP, etc.)
* **Goal**: Deliver early warning to clinicians with interpretable models

###  Modeling Pipeline

1. Data cleaning & interpolation
2. Feature extraction (rolling stats, slopes, time gaps)
3. Training with `XGBoost`, `RandomForest`, and `LSTM` models
4. Cross-validation & hyperparameter tuning
5. Model evaluation: precision, recall, AUROC, lead-time

###  Tools & Libraries:

```python
pandas, numpy, xgboost, keras, scikit-learn
```

###  Evaluation Metrics:

* F1-score
* AUROC
* Early warning lead-time (temporal precision)

### 🧠 Key Outcomes

* Gained real-world experience with **clinical time-series modeling**
* Learned the importance of **early detection** and **interpretable features**
* Explored ethical considerations and clinical impact
* Engaged with the Kaggle community and leaderboard analysis


---

## 🔚 Final Takeaways

* Solidified foundational and applied knowledge of GenAI
* Built end-to-end LLM applications using OpenAI tools and LangChain
* Gained practical insights from clinical ML in a high-stakes domain
* Ready to apply these skills in real-world AI solutions, from product to healthcare


