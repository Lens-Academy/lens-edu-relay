---
title: "A Full Description of an LLM"
source_url: https://ifanyonebuildsit.com/2/a-full-description-of-an-llm
published: 2025-09-16
author:
  - "Eliezer Yudkowsky"
  - "Nate Soares"
tags:
  - clippings
  - IABIED
  - work-in-progress
---
{--{"author":"AI","timestamp":1774206124157}@@
## A Full Description of an LLM

This resource provides a detailed technical explanation of Meta's Llama 3.1 405B language model, containing 405 billion parameters. The model was selected because it is "open-weights," meaning the parameters are publicly available.

### Core Architecture

**Tokenization and Embedding**: Words are broken into tokens across all supported languages. Each token converts to a vector of 16,384 numbers. The vocabulary contains 128,256 tokens. The embedding dictionary accounts for approximately 2 billion parameters.

**Attention Mechanism**: The distinctive feature of transformer models. Each activation vector transforms into 8 keys, 8 values, and 128 queries. Queries match against keys to retrieve weighted values. This allows tokens to "look around" at other tokens to determine meaning — for example, the word "right" queries neighboring words to determine if it means directional or correct.

**Feed-Forward Networks**: Uses SwiGLU variant. Expands 16,384-column rows to 53,248 columns, performs transformations, and compresses back.

**Full Architecture**: 126 layers total, each repeating the normalization-attention-residual-feedforward-residual sequence. Output projects to 128,256 probabilities (one per token) using softmax conversion.

### Computational Scale

- Processing 1,000 tokens requires approximately 810 trillion floating-point operations
- All 405 billion parameters are used for every single word processed
- Trained on 15.6 trillion tokens
- Approximately 38 septillion total computations during training

### The Scale of Inscrutability

No human presently knows what the parameter values mean. Reciting all parameters would require 5,133 years of continuous speech. Writing out calculations for processing a single token across 1,000-word input would take over 10 million years.

If all parameters were placed in an Excel spreadsheet on a standard screen, the spreadsheet would cover half the size of Manhattan.

### Comparative Complexity

Llama 3.1 405B is not yet as large as a human brain (approximately 100 trillion synapses). However, it can apparently talk like a person.

The authors emphasize that characterizing AIs as "just numbers" understates the genuine complexity involved, much as describing humans as "just biochemistry" would obscure meaningful understanding.--}{++{"author":"AI","timestamp":1774206124157}@@TODO: Re-scrape from website++}