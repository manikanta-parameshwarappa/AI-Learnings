# The Mechanics of Generative AI

## 1. The Paradigm Shift: Deterministic vs. Probabilistic

As Java developers, we are used to **Deterministic Systems**: *If input == A, then return B.* Generative AI introduces **Probabilistic Systems**. An LLM (Large Language Model) does not "retrieve" an answer from a database; it "calculates" the answer based on statistical likelihood.

When you ask "What is the capital of France?", the model isn't looking up a fact; it is predicting that the token "Paris" has the highest probability (e.g., 99.8%) of following that sequence. This shift requires a new mental model: we are no longer programming explicit logic, but rather orchestration and context management.
