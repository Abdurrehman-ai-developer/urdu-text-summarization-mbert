# Urdu Abstractive Text Summarization using mBERT-Large

A deep learning model for abstractive text summarization
in the Urdu language, built using Multilingual BERT Large
(mBERT-large) transformer architecture. This project tackles
the challenge of natural language understanding for Urdu —
a low-resource language with complex morphology and
right-to-left script.

---

## 🔍 Project Overview

Urdu is spoken by over 230 million people worldwide, yet
remains severely underrepresented in NLP research. This
model was fine-tuned on Urdu news and article datasets
using mBERT-large to generate abstractive summaries that
capture the core meaning of long Urdu texts in a concise,
human-like way.

Unlike extractive summarization which just copies sentences,
this model **generates new text** — producing natural,
fluent summaries in Urdu.

---

## 🧠 Model Architecture

- **Base Model:** Multilingual BERT Large (mBERT-large)
- **Task:** Abstractive Text Summarization
- **Language:** Urdu (اردو)
- **Framework:** PyTorch + HuggingFace Transformers
- **Tokenizer:** Multilingual BERT Tokenizer
- **Training:** Fine-tuned on custom Urdu news dataset

---

## 📊 Why mBERT-Large?

| Feature | mBERT-Base | mBERT-Large |
|---------|------------|-------------|
| Parameters | 110M | 340M |
| Hidden Layers | 12 | 24 |
| Attention Heads | 12 | 16 |
| Hidden Size | 768 | 1024 |
| Performance | Good | Superior |

mBERT-large provides significantly better understanding
of multilingual context, making it more suitable for
complex Urdu text summarization tasks.

---

## 📁 Project Structure

├── train_model.py            # Model training script
├── preprocessing.py          # Data preprocessing pipeline
├── tokenization.py           # Tokenization utilities
├── run_validation_mbert.py   # Validation and evaluation
├── final_results.jpg         # Final results screenshot
├── performance_charts.png    # Bar, line and radar charts
├── model_workflow.png        # Professional workflow diagram
└── README.md

---

## ⚙️ Installation

pip install transformers torch sentencepiece datasets
pip install bert-score rouge-score nltk

---

## 🚀 How to Use

# Step 1 - Preprocess your Urdu dataset
python preprocessing.py

# Step 2 - Fine-tune mBERT-large model
python train_model.py

# Step 3 - Run validation and evaluation
python run_validation_mbert.py

---

## 📈 Evaluation Metrics

This model was evaluated using standard
NLP summarization metrics:

- **ROUGE-1** — Unigram overlap score
- **ROUGE-2** — Bigram overlap score
- **ROUGE-L** — Longest common subsequence
- **BERTScore** — Semantic similarity score

---

## 🔄 Model Workflow

![Model Workflow](model_workflow.png)

---

## 📊 Performance Results

![Performance Charts](performance_charts.png)
![Final Results](final_results.jpg)

---

## 🆚 Model Comparison

| Model | Language | Parameters | Task |
|-------|----------|------------|------|
| mT5-base | Multilingual | 580M | Summarization |
| mBERT-large | Multilingual | 340M | Summarization |

Both models were fine-tuned and evaluated on the
same Urdu dataset for fair comparison.

---

## 🛠️ Tech Stack

- Python 3.x
- HuggingFace Transformers
- mBERT-Large Multilingual Model
- PyTorch
- Multilingual BERT Tokenizer
- ROUGE Evaluation Library
- Google Colab / GPU Training

---

## 📥 Download Trained Model

The fine-tuned model weights are available on HuggingFace:

[Download from HuggingFace Model Hub](your-huggingface-link)

---

## 👨‍💻 Author

**Abdur Rehman**
AI & ML Engineer | NLP Specialist
7+ Years Experience in AI Development
[Upwork Profile](https://www.upwork.com/freelancers/abdurrehmanaideveloper?mp_source=share)

---

## 🔗 Related Projects

- [Urdu Text Summarization using mT5-base]
(https://github.com/Abdurrehman-ai-developer/urdu-text-summarization-mt5)

---

## 📄 License

This project is licensed under the MIT License.
