# 🧠 LLM-from-Scratch: GPT-2 Inspired Causal Transformer

Welcome! This repository documents my journey building a **GPT-2 style causal Transformer model** entirely from scratch using PyTorch and Jupyter Notebooks. This hands-on project was both an incredible learning experience and a significant milestone in my path toward mastering LLM development.

---

## 🚀 Project Overview

🔹 This isn't a project that leans on pre-built libraries for attention, transformer blocks, or tokenizers.  
🔹 I implemented every component from scratch — including tokenization, embeddings, attention heads, and training loops.  
🔹 The final model closely resembles the GPT-2 architecture with **124 million parameters** and is pretrained on a novel titled **"The Verdict"**.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `LLM_tokenizer.ipynb` | Implements the custom tokenizer and byte-level encoding used to prepare the dataset. |
| `TransformerBlock.ipynb` | Builds the core transformer components: token & position embeddings, multi-head causal self-attention, layer normalization, MLP layers, and GELU activation. |
| `GPT_model_v1.ipynb` | Integrates everything into a complete GPT-2-style model and includes pretraining on the book *"The Verdict"*. |

---

## 🧠 Model Architecture

- **Parameters**: ~124M
- **Transformer Blocks**: 12
- **Context Length**: 1024
- **Embedding Dimension**: 768
- **Vocabulary Size**: 50,257
- **Activation Function**: GELU
- **Architecture**: Post-norm with LayerNorm → Attention → MLP (classic GPT-2 setup)

---

## 📚 Training Data

The model was pretrained on a text corpus derived from the novel **“The Verdict”**, allowing it to learn high-level text generation capabilities while remaining compact and manageable.

---

## 🔍 Highlights

- ✅ Manual implementation of causal multi-head attention
- ✅ Layer-wise construction with complete control
- ✅ Byte-level tokenization like OpenAI's GPT-2
- ✅ Fully functional forward pass
- ✅ Learned a ton about LLM internals along the way!

---

## 📈 Results

While this is an educational-scale model, it performs surprisingly well on next-token prediction tasks within the domain of the training text. The training process validated the model’s ability to learn meaningful representations and generate fluent completions.

---

## 🤝 Let's Connect!

I'm passionate about building in the LLM space and always open to discussing:
- 💬 Collaborations
- 🤖 Research opportunities
- 🧠 Advanced model scaling

📬 Feel free to reach out or connect with me on [LinkedIn](https://www.linkedin.com/in/dayanandk01)!

---

## 📜 License

This repository is released under the [MIT License](LICENSE).

---
