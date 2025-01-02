# Fine-tuning a T-lite for Chain-of-Thought problem solving

Fine tuning T-lite-it-1.0 on Russian thinking dataset


## Objective

The goal of this project is to fine-tune the T-Lite model (a Russian LLM that built upon the Qwen 2.5 7B) on structured Russian-language data, enabling it **to generate high-quality, step-by-step reasoning (chain-of-thought responses) and deliver well-formatted outputs**. The fine-tuning process will focus on improving the model's reasoning capabilities, adherence to formatting guidelines, and its ability to understand and respond to user queries effectively.

## Foundations

Model: [t-tech/T-lite-it-1.0-Q8_0-GGUF](https://huggingface.co/t-tech/T-lite-it-1.0-Q8_0-GGUF)

Dataset: [Russian thinking dataset](https://huggingface.co/datasets/Egor-AI/Russian_thinking_dataset)

Techniques: SFT, LoRA, quantization


## References to study

[smol course by Hugging Face](https://github.com/huggingface/smol-course)
