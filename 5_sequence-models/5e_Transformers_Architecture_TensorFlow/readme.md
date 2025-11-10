# Transformers Architecture with TensorFlow

This project implements the **core Transformer architecture** from scratch using **TensorFlow 2 / Keras**, following the assignment in **Week 4 – Sequence Models (DeepLearning.AI, Coursera)**.

## 🧠 Overview
The notebook walks through the fundamental building blocks of the Transformer model introduced in *“Attention is All You Need”*:

- Scaled Dot-Product Attention  
- Multi-Head Attention  
- Positional Encoding  
- Feed-Forward Network (FFN)  
- Residual Connections & Layer Normalization  
- Encoder Stack Assembly  

Each component is implemented step-by-step and then combined into a minimal functional encoder that can process tokenized sequences.

## ⚙️ Tools & Libraries
- Python 3.11  
- TensorFlow 2 / Keras  
- NumPy, Matplotlib  

## ▶️ How to Run
```bash
pip install tensorflow numpy matplotlib
jupyter notebook Transformers_Architecture_with_TensorFlow.ipynb
