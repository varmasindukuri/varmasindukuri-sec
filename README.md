# varmasindukuri-sec

> Building multi-agent ML systems for real-time threat detection

## Protector v2 — Multi-Model AI Security System

A 14-agent ensemble cybersecurity system running 24/7 on local endpoints.
Combines classical ML, deep learning, sequence modeling, and explainable AI
to detect, classify, and explain network intrusions and malware in real time.

### Architecture

| Notebook | Dataset | Models |
|----------|---------|--------|
| NB1 — Classical ML | CIC-IDS 2018 | SVM · Decision Tree · Random Forest · Naive Bayes · ELM · IsolationForest · Ensemble |
| NB2 — Deep Learning | UNSW-NB15 | CNN · LSTM · BiLSTM · GRU · ResNet-1D · GAN · Autoencoder |
| NB3 — Advanced | BETH | HMM · K-Means · HDBSCAN · Process2Vec · PCA2Vec · Transfer Learning |
| NB5 — Explainability | CIC-IDS 2018 | SHAP · GradCAM · Family Classifier · Stacking Ensemble |

### Endpoint (NB4)
- 14 agents fused via weighted majority vote + stacked meta-learner
- Attack family classification (BruteForce / DoS / Malware / WebAttack)
- SHAP explainability per prediction
- NetworkX process topology graphs
- Real-time VA scanner + static PE/YARA analysis
- Groq LLM Q&A with live system context
- Windows system tray — runs without Jupyter

### Datasets
- [CIC-IDS 2018](https://www.kaggle.com/datasets/) — 80 network flow features
- [UNSW-NB15](https://www.kaggle.com/datasets/) — 45 features, 9 attack categories
- [BETH](https://www.kaggle.com/datasets/) — host process logs + DNS logs

### Tech Stack
Python · scikit-learn · TensorFlow/Keras · SHAP · NetworkX · hmmlearn
hdbscan · gensim · psutil · pystray · Groq API

---

## Skills

**Machine Learning** — SVM · Random Forest · Gradient Boosting · Naive Bayes · ELM  
**Deep Learning** — CNN · LSTM · GRU · ResNet · GAN · Autoencoder  
**Explainable AI** — SHAP · GradCAM · Feature Importance  
**Cybersecurity** — IDS · Anomaly Detection · Malware Analysis · YARA · PE Analysis  
**MLOps** — Model Registry · Multi-Agent Fusion · Real-time Inference  

---

*Open to roles in: AI Security · Threat Intelligence · MLOps · Data Science*
