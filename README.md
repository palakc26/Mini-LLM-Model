# Mini LLM (Transformer from Scratch)

A small GPT-style language model built using PyTorch.

## Features
- Character/BPE tokenization
- RMSNorm
- Rotary Positional Embeddings (RoPE)
- Grouped Query Attention (GQA)
- SwiGLU feedforward
- Autoregressive text generation

## Training
- Dataset: Tiny Shakespeare
- Optimizer: AdamW
- Loss: CrossEntropy
- Hardware: Google Colab GPU

## Result
Model generates Shakespeare-style text after training.

## Tech Stack
PyTorch, Python, Colab
