
# YugAI – GPT-based Customer Support SLM (Small Language Model)

YugAI is a mobile-friendly, GPT-inspired **Small Language Model (SLM)** designed from scratch for **customer support** use cases. Built with performance and efficiency in mind, YugAI uses **Byte Pair Encoding (BPE)** and is trained to stay within tight **memory constraints (>90%)**, making it ideal for edge/mobile deployment.

---

## 🚀 Features

- 🧠 Lightweight architecture with **13.78M parameters**
- 📱 Mobile & edge-device friendly
- 🔤 Tokenized using **Byte Pair Encoding (BPE)**
- 🛠️ Fine-tuned for customer support scenarios
- 💾 Memory-efficient: uses >90% memory but avoids out-of-memory issues
- 📊 GFLOPs Theoretical Performance: **7.99 TFLOPs (~0.0079 PFLOPs)**

---

## 📐 Model Architecture

- **Embedding Shapes**: `(128, 256)` × 2
- **Total Parameters**: `13,785,088`
- **Tokens in Dataset**: `4,512,042`
- **Training Tokens (90%)**: `~4,060,837`
- **Batch Size**: `128 × 256 = 32,768 tokens`
- **Training Steps**: `~124`

---

## ⚙️ Training Setup

- **Tokenizer**: Byte Pair Encoding (BPE)
- **Framework**: PyTorch
- **Compute**: CUDA (NVIDIA GPU)
- **Theoretical GFLOPs Calculation**:


GFLOPs = CUDA Cores × Clock Speed × 2
\= 3328 × 1.2GHz × 2
\= 7987.2 GFLOPs = \~7.99 TFLOPs


---

## 📦 Use Cases

- Automated and intelligent **customer support chatbot**
- Context-aware **FAQ resolution**
- Mobile-based **text understanding** and response generation

---

## 🧪 Future Work

- LoRA/Quantization for further optimization
- Deployment as a REST API or ONNX/TF Lite mobile model
- Multi-turn conversation handling

---

## 📄 License

This project is for research and educational purposes only.

---
