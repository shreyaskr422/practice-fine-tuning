# 🧠 Practice Fine-Tuning

> A professional sandbox for experimenting with Large Language Model (LLM) fine-tuning techniques, including LoRA, QLoRA, and SFT.

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Transformers-FFD21E?style=for-the-badge)](https://huggingface.co/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

---

## 📖 Overview
This repository documents my implementation of various fine-tuning methodologies. The goal is to provide clean, reproducible scripts to adapt pre-trained models to specific tasks or datasets efficiently.

## ✨ Key Features
*   **PEFT Integration:** Implementation of LoRA and QLoRA for low-memory fine-tuning.
*   **Quantization:** Support for 4-bit and 8-bit loading using `bitsandbytes`.
*   **Evaluation:** Built-in scripts for loss tracking and model inference.
*   **Modular Design:** Separated data preprocessing, training logic, and configurations.

---

## 📂 Project Structure
```text
├── configs/             # Hyperparameter YAML/JSON files
├── notebooks/           # Interactive experiments & walkthroughs
├── scripts/             # Core Python training & inference scripts
├── data/                # Dataset loading & cleaning utilities
├── requirements.txt     # Dependency list
└── README.md            # Project documentation
```

---

## 🚀 Quick Start

### 1. Installation
```bash
# Clone the repository
git clone https://github.com/shreyaskr422/practice-fine-tuning.git
cd practice-fine-tuning

# Install dependencies
pip install -r requirements.txt
```

### 2. Basic Training
```bash
# Example: Run a fine-tuning script
python scripts/train.py --model_name "gpt2" --dataset "path/to/data"
```

---

## 📊 Results
| Model | Dataset | Technique | Training Loss |
| :--- | :--- | :--- | :--- |
| **Llama-3-8B** | Alpaca-Clean | QLoRA | 0.452 |
| **Mistral-7B** | Custom Instructions | LoRA | 0.318 |
| **GPT-2** | Wiki-Text | Full Fine-Tune | 0.821 |

---

## 🛠️ Tech Stack
- **Frameworks:** PyTorch, Transformers, Accelerate
- **Optimization:** DeepSpeed, PEFT (LoRA), BitsAndBytes
- **Logging:** Weights & Biases / TensorBoard

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/shreyaskr422">shreyaskr422</a></sub>
</div>
