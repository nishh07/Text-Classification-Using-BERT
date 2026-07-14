# 📰 Text Classification Using BERT

## 📌 Overview

This project implements a **Text Classification system** using **BERT (Bidirectional Encoder Representations from Transformers)**. The model is fine-tuned on the **AG News Classification Dataset** to classify news articles into predefined categories.

The project demonstrates the complete NLP pipeline, including data preprocessing, tokenization, model fine-tuning, evaluation, and prediction using the Hugging Face Transformers library and PyTorch.

---

## 🚀 Features

- Fine-tuned BERT model for text classification
- Natural Language Processing (NLP)
- Data preprocessing and cleaning
- Tokenization using Hugging Face Tokenizer
- Model training and validation
- Performance evaluation using Accuracy and Macro F1-score
- Prediction on unseen news articles
- Model saving for future inference

---

## 🛠 Technologies Used

- Python
- BERT (prajjwal1/bert-tiny)
- Hugging Face Transformers
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Kaggle Notebook

---

## 📂 Dataset

**Dataset Used:**

AG News Classification Dataset

The dataset contains thousands of news articles divided into four categories:

- World
- Sports
- Business
- Science & Technology

Each record contains:

- News Title
- News Description
- Category Label

---

## 🔄 Project Workflow

### 1. Data Collection

- Load AG News training and testing datasets.
- Combine title and description into a single text feature.

---

### 2. Data Preprocessing

- Handle missing values.
- Clean and prepare textual data.
- Convert category labels into numerical format.

---

### 3. Tokenization

- Load the BERT tokenizer using Hugging Face.
- Convert text into input IDs and attention masks.
- Apply padding and truncation for uniform sequence length.

---

### 4. Model Development

- Load a pre-trained BERT model.
- Fine-tune the model for sequence classification.
- Configure the classifier with four output classes.

---

### 5. Model Training

- Train the model using the Hugging Face Trainer API.
- Optimize model weights through multiple training epochs.
- Monitor validation performance during training.

---

### 6. Model Evaluation

The trained model is evaluated using:

- Accuracy
- Macro F1-Score
- Classification Report
- Confusion Matrix

---

### 7. Prediction

The trained model can classify new text into one of the supported news categories.

Example:

Input:

Apple launches its latest AI-powered smartphone.

Prediction:

Science & Technology

---

## 📊 Results

The fine-tuned BERT model demonstrates strong text classification performance by learning contextual representations of text and accurately categorizing news articles.

Performance is evaluated using:

- Accuracy
- Macro F1 Score
- Precision
- Recall

---

## 📁 Project Structure

```
Text-Classification-Using-BERT
│
├── textclassification_bert_finetuning_payt.ipynb
├── README.md
├── .gitignore
└── requirements.txt (optional)
```

---

## 💡 Skills Demonstrated

- Natural Language Processing (NLP)
- Deep Learning
- Transfer Learning
- Transformer Models
- BERT Fine-Tuning
- Text Classification
- Data Preprocessing
- Machine Learning
- Model Evaluation
- Python Programming

---

## 🎯 Future Enhancements

- Deploy the model using Flask or FastAPI
- Create a web interface using Streamlit
- Support multilingual text classification
- Experiment with RoBERTa and DistilBERT models
- Improve accuracy through hyperparameter tuning

---

## 👨‍💻 Author

**Kuchi Sai Krishna**

- GitHub: https://github.com/Saikrishna58397
- LinkedIn: https://www.linkedin.com/in/k-sai-krishna-773b362a5

---

## ⭐ If you found this project useful, consider giving it a Star!
