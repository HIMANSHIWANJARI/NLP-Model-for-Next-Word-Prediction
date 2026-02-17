# NLP-Model-for-Next-Word-Prediction

## Overview

This project implements a **Next Word Prediction system** using Natural Language Processing (NLP) techniques. The model predicts the next word in a sentence based on previously given words by learning patterns from text data.

The goal is to understand sequential language structure and generate context-aware word predictions.

---

## Objective

* Build an NLP-based language model for next-word prediction
* Process and understand text sequences
* Generate context-aware predictions based on input text

---

## Technologies Used

* Python
* TensorFlow 
* Natural Language Processing (NLP)
* Bidirectional LSTM
* Kaggle Dataset

---

## Data Preprocessing

### Tokenization

* Text is converted into numerical format using a tokenizer.
* Each word is assigned a unique integer value.

### Sequence Padding

* Input sequences are padded so that all sequences have equal length.
* This helps maintain consistent input format.

---

## Model Architecture

### Embedding Layer

* Converts words into vector representations.
* Helps capture relationships between words.

### Bidirectional LSTM

* Processes sequences to understand context from previous words.
* Learns patterns in text sequences.

### Dense Layer

* Produces probability scores for possible next words.
* Outputs the most likely prediction.

---

## Model Training

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Evaluation Metric: Accuracy

The model is trained on text sequences and validated during training to monitor performance.

---

##  Features

 Context-aware next word prediction
 NLP-based text preprocessing
 Sequential language modeling
 Probability-based word prediction

---

## How to Run

Install dependencies:

```
pip install -r requirements.txt
```

Train the model:

```
python train.py
```

Run prediction:

```
python predict.py
```

---

## Conclusion

This project demonstrates how NLP techniques can be used to build a language model capable of predicting the next word in a sentence based on context and learned text patterns.


