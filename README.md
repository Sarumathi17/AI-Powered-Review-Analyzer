# AI-Powered Review Analyzer using Fine-Tuned BERT

## 📌 Project Overview

This project is a Transformer-based NLP application that performs sentiment analysis on movie reviews using a fine-tuned DistilBERT model from HuggingFace.  
The model classifies reviews as **Positive** or **Negative** by understanding the contextual meaning of text rather than relying on traditional keyword-based approaches.

The project demonstrates:
- Natural Language Processing (NLP)
- Transformer Architecture
- HuggingFace Tokenization
- Transfer Learning
- Fine-Tuning BERT Models
- Model Evaluation & Visualization

---

# 🚀 Features

✅ Sentiment Analysis using Transformer Models  
✅ Fine-Tuned DistilBERT on Custom Dataset  
✅ HuggingFace Tokenizer Integration  
✅ Context-Aware Text Understanding  
✅ Model Evaluation using Accuracy & Classification Report  
✅ Confusion Matrix Visualization  
✅ Real Review Predictions  

---

# 🧠 Technologies Used

- Python
- PyTorch
- HuggingFace Transformers
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

---

# 📂 Dataset

The project uses a custom movie review dataset containing:
- Review Text
- Sentiment Labels (Positive / Negative)

The labels were encoded as:
- `0 → Negative`
- `1 → Positive`

---

# 🔄 Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Label Encoding
   ↓
Train-Test Split
   ↓
Tokenization using HuggingFace
   ↓
Pretrained DistilBERT
   ↓
Fine-Tuning
   ↓
Evaluation
   ↓
Visualization
```
---

# 🤖 Model Used

## DistilBERT

```python
distilbert-base-uncased-finetuned-sst-2-english
```

DistilBERT is a lightweight and faster version of BERT that retains strong language understanding capabilities while reducing computational complexity.

---

# 🔥 Fine-Tuning

The pretrained DistilBERT model was further fine-tuned on the custom review dataset using the HuggingFace Trainer API.

Hyperparameter tuning was performed by adjusting:

- Number of epochs
- Batch size
- Maximum sequence length

This improved the model’s ability to adapt to the custom dataset.

---

# 📊 Results

| Model | Accuracy |
|------|----------|
| Pretrained DistilBERT | 84% |
| Fine-Tuned DistilBERT | 84.8% |

The fine-tuned model demonstrated improved contextual understanding and better sentiment classification performance.

---

# 📈 Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- 
---

# 💡 Key Learnings

- Understanding Transformer Architecture
- HuggingFace Tokenization
- Self-Attention Mechanism
- Transfer Learning in NLP
- Fine-Tuning Transformer Models
- Hyperparameter Tuning
- Model Evaluation Techniques

---

# 🔮 Future Enhancements

- Deploy using Streamlit
- Add multilingual sentiment analysis
- Use larger datasets
- Add review summarization
- Build a web-based NLP application

---

# 👩‍💻 Author

**Sarumathi M**

Aspiring Data Scientist | AI & NLP Enthusiast
