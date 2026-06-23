<div align="center">

# 🎬 IMDb Movie Review Sentiment Analysis using RNN with PyTorch

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org)
[![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-blueviolet?style=for-the-badge)](#)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Dataset](https://img.shields.io/badge/Dataset-IMDb%20Reviews-blue?style=for-the-badge)](https://ai.stanford.edu/~amaas/data/sentiment/)

> A Deep Learning Natural Language Processing (NLP) project built with PyTorch that uses a Recurrent Neural Network (RNN) to classify IMDb movie reviews as positive or negative.

</div>

---

# 🎯 Project Overview

This project demonstrates how to build and train a Recurrent Neural Network (RNN) for sentiment analysis using PyTorch.

The model learns patterns from movie review text and predicts whether a review expresses a positive or negative sentiment.

The RNN achieved **85.16% test accuracy** on unseen IMDb movie reviews.

The project covers the complete NLP workflow:

- Text preprocessing
- Sequence preparation
- Sentiment classification
- RNN model building
- Model training
- Accuracy evaluation
- Performance analysis

---

# 📌 Problem Statement

Understanding customer opinions from text data is one of the most important tasks in Natural Language Processing.

Movie reviews contain valuable information about audience satisfaction and sentiment.

This project uses a Recurrent Neural Network (RNN) to automatically classify IMDb movie reviews into positive and negative categories.

---

# 📊 Dataset Information

The project uses the IMDb Movie Reviews Dataset.

### Dataset Details

| Property | Value |
|-----------|---------|
| Dataset | IMDb Reviews |
| Task | Sentiment Analysis |
| Classes | 2 |
| Classification Type | Binary Classification |

---

# 🏷️ Sentiment Classes

The model predicts:

- 😊 Positive Review
- 😞 Negative Review

---

# 🚀 Features

- Natural Language Processing (NLP)
- Sentiment Analysis
- Binary Text Classification
- Recurrent Neural Network (RNN)
- Sequence-Based Learning
- Deep Learning using PyTorch
- Accuracy Evaluation
- Real-World Text Classification

---

# 🧠 NLP Pipeline

## Data Preparation

- Load IMDb Reviews Dataset
- Convert Reviews into Numerical Features
- Create Training and Testing Sets
- Build DataLoaders
- Batch Processing

## Model Development

- Build RNN Architecture
- Learn Sequential Patterns
- Extract Contextual Information
- Generate Sentiment Predictions

## Training Process

- Forward Propagation
- Loss Calculation
- Backpropagation
- Weight Optimization using Adam Optimizer

## Evaluation

- Test Dataset Prediction
- Accuracy Calculation
- Model Performance Analysis

---

# 🏗️ RNN Architecture

```text
Input Review Features

        ↓

RNN Layer
(Hidden Size = 128)

        ↓

Final Hidden State

        ↓

Fully Connected Layer
(128 → 1)

        ↓

Sigmoid Activation

        ↓

Positive / Negative Sentiment
```

---

# ⚙️ Model Hyperparameters

| Parameter | Value |
|------------|--------|
| Framework | PyTorch |
| Model | RNN |
| Hidden Size | 128 |
| Number of Layers | 1 |
| Optimizer | Adam |
| Loss Function | BCELoss |
| Task | Sentiment Analysis |
| Classes | 2 |
| Epochs | 10 |

---

# 📈 Model Results

| Metric | Score |
|---------|---------|
| Test Accuracy | **85.16%** |
| Dataset | IMDb Reviews |
| Classes | 2 |
| Epochs | 10 |

### Training Loss

| Epoch | Loss |
|---------|---------|
| 1 | 0.149 |
| 2 | 0.156 |
| 3 | 0.264 |
| 4 | 0.269 |
| 5 | 0.356 |
| 6 | 0.137 |
| 7 | 0.133 |
| 8 | 0.130 |
| 9 | 0.330 |
| 10 | 0.318 |

The RNN achieved **85.16% test accuracy** on the IMDb sentiment analysis dataset, successfully classifying movie reviews as positive or negative.

---

# 🔍 Example Predictions

### Example 1

Review:

> "This movie was absolutely fantastic. The acting was brilliant and the story kept me engaged throughout."

Prediction:

✅ Positive Review

---

### Example 2

Review:

> "Worst movie I have ever watched. The plot made no sense and the acting was terrible."

Prediction:

❌ Negative Review

---

# 📂 Project Structure

```text
IMDb-Movie-Review-Sentiment-Analysis-using-RNN-with-PyTorch/
│
├── RNN_for_sentimentanalysis.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

---

# 🖥️ Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/harsh-v16/-IMDb-Movie-Review-Sentiment-Analysis-using-RNN-with-PyTorch.git

cd -IMDb-Movie-Review-Sentiment-Analysis-using-RNN-with-PyTorch
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Notebook

```bash
jupyter notebook RNN_for_sentimentanalysis.ipynb
```

---

# 📦 Dependencies

| Package | Purpose |
|----------|----------|
| PyTorch | Deep Learning Framework |
| NumPy | Numerical Computing |
| Pandas | Data Processing |
| Matplotlib | Visualization |
| Jupyter | Notebook Environment |

---

# 🛠️ Tech Stack

| Tool | Purpose |
|------|----------|
| Python | Programming Language |
| PyTorch | Deep Learning Framework |
| NumPy | Numerical Computing |
| Pandas | Data Processing |
| Matplotlib | Data Visualization |
| Jupyter Notebook | Development Environment |
| GitHub | Version Control |

---

# 📚 Learning Outcomes

Through this project, I learned:

- Text Preprocessing for NLP
- Sequence-Based Learning
- Recurrent Neural Networks (RNNs)
- Hidden State Representation
- Sentiment Analysis
- Binary Text Classification
- Deep Learning for Natural Language Processing
- Model Training and Evaluation
- Working with Real-World Text Data
- Accuracy-Based Performance Analysis

---

# 🔮 Future Improvements

- LSTM-Based Sentiment Analysis
- GRU-Based Architecture
- Attention Mechanisms
- Pretrained Word Embeddings
- Transformer Models
- BERT Fine-Tuning
- Streamlit Deployment

---

# 👤 Author

<div align="center">

**Harsh Chaudhary**

Computer Engineering Student | Machine Learning & Deep Learning Enthusiast

[![GitHub](https://img.shields.io/badge/GitHub-harsh--v16-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/harsh-v16)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Harsh%20Chaudhary-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harsh-chaudhary-6ba5b8395/)

</div>

---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>
