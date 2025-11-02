# Albanian Hate Speech Detection using Structural Pattern Recognition

This repository contains the implementation of a **hybrid hate speech detection framework** that leverages **structural pattern recognition** through the **Enhanced Manacher Algorithm** in combination with **TF-IDF semantic features**.  
The system is designed for the **Albanian language**, addressing a major research gap in multilingual hate speech detection where low-resource languages often lack high-quality annotated datasets and specialized models.

---

## Motivation

The rapid growth of social media and online communication has led to an alarming increase in **hate speech**, targeting individuals and groups based on ethnicity, gender, religion, and sexual orientation.  
While existing approaches rely heavily on deep learning or pre-trained transformers, these models are often computationally expensive and difficult to interpret — especially in **resource-constrained environments**.

This project introduces a **lightweight, interpretable, and efficient** model that captures **linguistic structure and repetition** — traits often found in hate speech patterns — without requiring massive data or GPU resources.

---

## Research Objective

The primary goal of this study is to design and evaluate a **structural pattern recognition model** capable of identifying hate speech in Albanian text. Specifically, the project aims to:

1. Implement an **Enhanced Manacher Algorithm** for structural feature extraction.
2. Combine structural features with **TF-IDF** to integrate semantic and syntactic cues.
3. Evaluate multiple machine learning models on the hybrid feature set.
4. Analyze model performance, computational cost, and interpretability.
