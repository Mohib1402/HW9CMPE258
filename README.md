---


# 🧠 Keras NLP Tasks – Transformers, Fine-Tuning, and Custom Models

This repository contains three Google Colab notebooks demonstrating key NLP tasks using `KerasNLP` and `Hugging Face Transformers`. Each notebook is accompanied by a video walkthrough that includes debugging traces and model interpretation.

## 🔍 Project Structure

| Notebook | Task | Description |
|---------|------|-------------|
| `1_inference_pretrained_classifier.ipynb` | Inference | Uses Hugging Face's `pipeline` with `DistilBERT` for sentiment classification |
| `2_fine_tuning_bert_imdb.ipynb` | Fine-Tuning | Fine-tunes `BERT` on the IMDb dataset using Hugging Face `Trainer` API |
| `3_transformer_from_scratch_keras.ipynb` | From-Scratch | Builds a Transformer encoder from scratch using only `tf.keras` layers |

---

## 📁 Contents

### ✅ `1_inference_pretrained_classifier.ipynb`
- Uses `transformers.pipeline` for zero-shot sentiment classification.
- Debug trace includes:
  - Token IDs and attention masks
  - Raw logits and softmax confidence
- 🔗 **Video Walkthrough**: [Watch here](https://colab.research.google.com/drive/1lKCkH4wXhfDL5K97_DaFO9Ho1E60vp3v?usp=sharing)

---

### ✅ `2_fine_tuning_bert_imdb.ipynb`
- Fine-tunes `bert-base-uncased` on IMDb with Hugging Face `datasets`.
- Evaluated using accuracy on test set.
- Predicts on custom sentences post fine-tuning.
- 🔗 **Video Walkthrough**: [Watch here](https://colab.research.google.com/drive/1iN7jsQlt4KxbFy3CDGxr-cXC8SU4ZxfL?usp=sharing)

---

### ✅ `3_transformer_from_scratch_keras.ipynb`
- Implements Transformer encoder block from scratch:
  - Positional embeddings
  - Multi-head attention
  - Feed-forward network
- Trained on IMDb dataset (token IDs) using `tf.keras`.
- Includes plots for accuracy and loss + custom input prediction.
- 🔗 **Video Walkthrough**: [Watch here](https://colab.research.google.com/drive/1gWdG3vo1cOqlSt6agLkhJsImVwnZNo3d?usp=sharing)

---

## 🛠 Setup

All notebooks are runnable in **Google Colab**. Required packages:

```bash
pip install transformers datasets scikit-learn tensorflow
```

---

## 🧪 Inference Examples

```python
predict_sentiment("I loved the characters and story!") 
# Output: Positive (0.9812)
```

---

## 📹 Videos

Each notebook has a demo walkthrough (with debug traces):

* 📼 [Walkthrough](#)

---

## ✍️ Author

* **Mohibkhan Pathan** – Graduate Student @ SJSU
* Course: CMPE 258 — Prof. Vijay Eranti

---
