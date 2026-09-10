# Bigram Language Model

A simple character-level Bigram Language Model built using PyTorch to understand the fundamentals of Large Language Models (LLMs). This project demonstrates how a model learns the probability of the next character based solely on the current character and generates text by sampling from the learned distribution.

## Overview

The Bigram Language Model is one of the simplest language models. Given a character, it predicts the next character using learned probability distributions. While simple, it introduces key concepts used in modern LLMs such as:

* Tokenization
* Embeddings
* Probability distributions
* Training with gradient descent
* Text generation
* Loss optimization

This project was built as part of my journey into understanding how modern language models work from the ground up.

## Features

* Character-level tokenization
* Bigram-based next-token prediction
* PyTorch implementation
* Training loop with loss tracking
* Text generation through sampling
* Simple and beginner-friendly code structure

## Tech Stack

* Python
* PyTorch
* NumPy

## Project Structure

```text
bigram-language-model/
│
├── data/
│   └── input.txt
│
├── model.py
├── train.py
├── generate.py
├── requirements.txt
└── README.md
```

## How It Works

1. The dataset is converted into character tokens.
2. Each character is mapped to an integer index.
3. The model learns transition probabilities between characters.
4. Cross-entropy loss is used for optimization.
5. After training, the model generates new text one character at a time.

## Installation

```bash
git clone <repository-url>
cd bigram-language-model
pip install -r requirements.txt
```

## Training

```bash
python train.py
```

The model will train on the provided dataset and display the training loss during optimization.

## Text Generation

```bash
python generate.py
```

After training, the model can generate new text by predicting one character at a time based on learned probabilities.

## Sample Output

```text
The king was in the hall and the people gathered around...
```

(The generated text depends on the training dataset and model parameters.)

## Learning Outcomes

Through this project, I gained hands-on experience with:

* Language modeling fundamentals
* Tokenization techniques
* Neural network training
* Embedding layers
* Loss functions and optimization
* Text generation pipelines
* Core concepts behind modern LLMs

## Future Improvements

* Multi-layer neural networks
* Self-attention mechanism
* Transformer architecture
* GPT-style autoregressive models
* Larger datasets and vocabulary handling

## Author

Bindusree Kunuru

Computer Science Engineering Student | AI & Machine Learning Enthusiast
