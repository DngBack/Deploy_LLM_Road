# Introduction to Parameter-Efficient Fine-Tuning (PEFT) in Hugging Face

## Overview

PEFT optimizes fine-tuning of large language models by modifying a small subset of parameters, reducing computational cost and memory usage while maintaining performance.

## Traditional Approaches

- **Pre-training**: Learning general representations from large datasets.
- **Fine-tuning**: Updating all model parameters for a specific task.

PEFT provides a more efficient alternative.

## Key PEFT Techniques

### 1. Adapter Tuning

Adds small trainable layers (adapters) to a frozen model for task-specific learning.

### 2. LoRA (Low-Rank Adaptation)

Injects low-rank matrices into transformer layers, reducing trainable parameters.

### 3. Quantization

Reduces model weight precision, optimizing size and inference speed.

### 4. Prompt Modifications

Instead of updating weights, modifies inputs:

- **Hard Prompt**: Manually designed text prompts.
- **Soft Prompt**: Trainable embeddings for adaptive input modifications:
  - **Prompt Tuning**: Optimizing continuous prompt tokens.
  - **Prefix Tuning**: Adjusting prefix activations.
  - **P-tuning**: Learning continuous prompt embeddings.

## Benefits of PEFT

- **Efficiency**: Reduces trainable parameters, lowering costs.
- **Scalability**: Enables tuning large models on limited resources.
- **Modularity**: Adapts pre-trained models for various tasks.
- **Performance**: Maintains accuracy with fewer resources.

## Conclusion

PEFT, available in the Hugging Face `peft` library, streamlines fine-tuning with techniques like LoRA, adapter tuning, and prompt modifications, making model adaptation more accessible and efficient.

## Table of Contents

- [QLoRA](./notebook/QLoRA_Tuning_PEFT.ipynb)
