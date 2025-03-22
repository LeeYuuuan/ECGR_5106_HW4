# ECGR_5106_HW4

This repository contains the implementation of sequence-to-sequence models for English-French translation using PyTorch, as part of ECGR 5106 Homework 4.

## 📁 Files

- **Problem_1.ipynb**  
  Implements a GRU-based encoder-decoder model for English-to-French translation without attention.

- **Problem_2.ipynb**  
  Enhances the model by adding an attention mechanism to improve translation accuracy.

- **Problem_3.ipynb**  
  Reverses the translation direction (French-to-English) and compares performance with Problem 2.

## 📌 Highlights

- Word-level GRU encoder-decoder architecture.
- Attention mechanism improves contextual understanding.
- Accuracy and generalization performance evaluated on both directions.
- Includes qualitative and quantitative analysis.

## 🧪 Results Summary

- **P1**: GRU achieves perfect training accuracy, but poor generalization.
- **P2**: Attention improves performance over basic GRU.
- **P3**: French-to-English translation is more challenging; attention still helps but accuracy is lower.

---

Feel free to explore each notebook for implementation details and evaluation results.
