# LLM Fine-Tuning Studio 🧪

**Efficient LLM Adaptation Framework**

A modular, high-performance framework for fine-tuning Large Language Models (LLMs) on consumer and enterprise hardware. It abstracts the complexities of PEFT (Parameter-Efficient Fine-Tuning) and quantization, enabling developers to adapt models like Llama 3 and Mistral to specific domains.

## ⚡ Optimization Techniques

-   **QLoRA (Quantized LoRA)**: Reduces memory usage by 50% using 4-bit NormalFloat quantization, allowing 70B models to be fine-tuned on a single A100.
-   **Flash Attention 2**: Integrated for 3x faster training throughput.
-   **Gradient Checkpointing**: Optimizes VRAM usage for larger batch sizes.

## 🚀 Key Features

-   **Dataset Streaming**: Efficiently handles terabyte-scale datasets using Hugging Face streaming.
-   **Experiment Tracking**: Native integration with Weights & Biases for visualizing loss curves and hyperparameters.
-   **Model Merging**: Utilities to merge LoRA adapters back into the base model for deployment.

## 🛠️ Supported Models

-   **Llama 3 (8B, 70B)**
-   **Mistral 7B / Mixtral 8x7B**
-   **Gemma / Phi-3**

## 📄 License
MIT License
