# Face Recognition with FaceNet (DeepLearning.AI CNN Module – Week 4)

This project implements a **face verification and recognition system** using **FaceNet-style embeddings**.  
It is part of *Course 4 – Convolutional Neural Networks* in the **DeepLearning.AI Deep Learning Specialization** by Andrew Ng.

## 🧠 Overview
The goal is to train and evaluate a system that can:
- **Verify** whether two images belong to the same person (1:1 matching)
- **Recognize** an individual’s identity among many (1:K matching)

A pre-trained **FaceNet** model is used to map each face image to a **128-dimensional embedding vector**.  
Similarity between embeddings is measured using **L2 distance**, and the network is optimized via the **triplet loss** function.

## 🧩 Concepts Demonstrated
- One-shot learning for face recognition  
- **Triplet loss** for metric learning  
- 128-D facial embeddings using a pretrained ConvNet  
- **Face verification vs. face recognition** distinction  
- Using pretrained models for transfer learning  

## ⚙️ Tools & Dependencies
- Python 3.11  
- TensorFlow / Keras  
- NumPy, Matplotlib  
- Pretrained FaceNet weights (`keras-facenet-tf23`, `nn4.small2.v7.h5`)  