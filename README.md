# Spam_Detection_Word2Vec_NN

### **README.md for Spam Detection with Word2Vec & Neural Network**
```markdown
# Spam Detection using Word2Vec and Neural Network

## Overview
This project implements a **Spam Detection system** using:
1. **Word2Vec (Manually Implemented)**
2. **Feed-Forward Neural Network**

## Dataset
- **Spam or Not Spam Dataset** from Kaggle.

## Features Implemented
- **Data Preprocessing**
  - Lowercasing, Tokenization
  - Stopword Removal
  - Dataset Balancing (Undersampling)

- **Word2Vec (Implemented from Scratch)**
  - Uses **Negative Sampling**
  - Embedding Size: `10`
  - Context Window: `2`

- **Feed-Forward Neural Network**
  - **Input:** 12 words, each with 10-dimensional embedding.
  - **Hidden Layer:** 8 neurons.
  - **Output:** 1 neuron (Spam or Not-Spam)

- **Model Evaluation**
  - Accuracy, Precision, Recall, F1 Score
  - Confusion Matrix for performance evaluation

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/NLP_Spam_Detection_Word2Vec_NN.git
   cd NLP_Spam_Detection_Word2Vec_NN




