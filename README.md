[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PQflKwu4FDxe5x800lBfaGZkZE589M4t#scrollTo=2DSu3DS3-Vzu)

# Federated Learning for Question Answering (NLP)

## 🚀 Overview
This project implements a privacy-preserving Question Answering system using Federated Learning.

- Framework: Flower (flwr)
- Model: DistilBERT
- Dataset: SQuAD v1.1
- Strategy: FedAvg

## 🔐 Key Idea
Training happens locally on multiple clients.
Only model updates are shared — raw data is never exposed.

## 🧠 Features
- Federated Learning simulation using Flower
- Extractive QA using DistilBERT
- Client-server architecture
- Privacy-preserving training
- End-to-end pipeline (data → training → inference)

## ⚙️ Tech Stack
- Python
- PyTorch
- HuggingFace Transformers
- Flower (FL framework)
- Datasets

## 📊 Results
- Successfully trained global model using federated aggregation
- Model can answer questions from unseen context

## 📌 How to Run

1. Open notebook in Google Colab
2. Install dependencies
3. Run all cells

## 🔮 Future Improvements
- Increase number of clients and rounds
- Add Differential Privacy
- Use non-IID data
- Scale to larger models (LLMs)

## 👨‍💻 Author
Prasad Nikam
