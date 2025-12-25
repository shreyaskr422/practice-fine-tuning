# 🧠 Practice Fine-Tuning

Minimalist toolkit for efficient LLM adaptation using PEFT, LoRA, and QLoRA.


## ⚡ Features
- **Efficient Tuning:** Implementation of LoRA & QLoRA via `peft`.
- **Memory Optimized:** 4-bit and 8-bit quantization with `bitsandbytes`.
- **Flexible:** Support for Llama, Mistral, and Phi-series models.

## 📂 Structure
```text
├── notebooks/   # Interactive experiments
├── scripts/     # Training and inference logic
├── configs/     # Training hyperparameters
└── data/        # Preprocessing utilities
```

## 🚀 Getting Started

### 1. Setup
```bash
git clone https://github.com/shreyaskr422/practice-fine-tuning.git
pip install -r requirements.txt
```

### 2. Train
```bash
python scripts/train.py --config configs/default.yaml
```

## 🛠️ Stack
- **Framework:** PyTorch
- **Libraries:** Transformers, PEFT, Accelerate
- **Logging:** Weights & Biases (W&B)

---
[MIT License](LICENSE) • Built by [shreyaskr422](https://github.com/shreyaskr422)
