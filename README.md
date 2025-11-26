# LLM Fine-Tuning Studio 🧪

A modular framework for fine-tuning Large Language Models (LLMs) using efficient techniques like LoRA and QLoRA.

## 🎯 Features

-   **Efficient Training**: Support for PEFT (Parameter-Efficient Fine-Tuning) methods.
-   **Quantization**: 4-bit and 8-bit quantization via bitsandbytes.
-   **Dataset Management**: Easy integration with Hugging Face Datasets.
-   **Experiment Tracking**: Integration with Weights & Biases.
-   **Model Export**: Merge adapters and export to GGUF/ONNX.

## 🛠️ Supported Models

-   Llama 3
-   Mistral 7B
-   Falcon
-   Gemma

## 📦 Getting Started

### Prerequisites
-   NVIDIA GPU (min 16GB VRAM recommended)
-   Python 3.10+

### Usage

1.  **Configure Training**:
    Edit `configs/lora_config.yaml` to set hyperparameters.

2.  **Start Training**:
    ```bash
    python scripts/train.py --config configs/lora_config.yaml
    ```

## 📄 License
MIT License
