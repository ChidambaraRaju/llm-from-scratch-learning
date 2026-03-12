# LLM From Scratch — Learning Journey

This repository documents my journey learning the internal mechanisms of Large Language Models (LLMs) by implementing core components from scratch.

The notebooks in this repository are based on the Udemy course:

**A deep understanding of AI large language model mechanisms** by Mike X Cohen.

The goal is to deeply understand how modern LLMs work internally rather than treating them as black-box APIs.

---

# Objectives

The main objectives of this learning journey are:

- Understand how text is converted into tokens
- Learn how embeddings represent language in vector space
- Implement attention mechanisms
- Build transformer blocks
- Understand GPT-style architectures
- Train a small language model
- Fine-tune pretrained models

The ultimate goal of this learning process is to build a **Small Language Model (SLM) from scratch**.

---

# Topics Covered

## 1. Tokenization

- Why text must be converted to numbers
- Character vs word vs subword tokenization
- Byte Pair Encoding (BPE)
- Vocabulary construction
- Token statistics and compression ratios

---

## 2. Embeddings

- Word embeddings
- Embedding spaces
- Cosine similarity
- Positional embeddings
- Training embeddings from scratch
- Exploring pretrained embeddings (GloVe, GPT2, BERT)

---

## 3. Transformer Fundamentals

- Softmax and probability distributions
- Sampling strategies
- Layer normalization
- Feedforward networks
- Residual connections

---

## 4. Attention Mechanism

- Self-attention
- Query, Key, Value matrices
- Causal masking
- Single-head attention
- Multi-head attention

---

## 5. Transformer Blocks

- Transformer architecture
- Stacking attention blocks
- Feedforward layers
- Parameter scaling

---

## 6. GPT Architecture

- Decoder-only transformers
- Token embeddings
- Positional embeddings
- Multi-head self-attention
- Transformer blocks
- Output projection

---

## 7. Pretraining Language Models

- Training loops in PyTorch
- Cross entropy loss
- Adam / AdamW optimizers
- Weight initialization
- Dropout
- Dataset preparation

---

## 8. Fine-Tuning

- Fine-tuning GPT models
- Learning rate strategies
- Freezing model layers
- Parameter-efficient fine tuning concepts

---

# Learning Approach

For each concept:

1. Study the theoretical explanation
2. Implement the concept in code
3. Run experiments
4. Document observations in notebooks

This repository is intentionally exploratory and focuses on **understanding LLM internals through hands-on experimentation.**