

# Chatbot 

This project implements an intelligent chatbot built using the **Qwen3-4B-Instruct** model.
It leverages modern NLP techniques, efficient text generation, and an interactive Gradio interface to provide a smooth conversational experience.

---

##  Features

* Uses **Qwen/Qwen3-4B-Instruct-2507** for high-quality responses.
* Fast inference with **4-bit quantization** for low GPU memory usage.
* Clean prompt construction using chat templates.
* Modern NLP stack: Transformers, Attention, and deep learning generation.
* Simple and responsive **Gradio UI** for user interaction.

---

## 📌 Tech Stack

* **Python**
* **Transformers**
* **Accelerate**
* **BitsAndBytes (4-bit load)**
* **PyTorch**
* **Gradio**

---


---

##  How It Works

1. Load the tokenizer and model from Hugging Face.
2. Build a text-generation pipeline with optimized settings.
3. Construct prompts using a system + user message template.
4. Generate a response using controlled decoding (temperature, top-p).
5. Display results through a simple Gradio interface.

---

##  Usage

Install dependencies:

```bash
pip install -q transformers accelerate bitsandbytes gradio torch
```

Run the chatbot:

```bash
python app.py
```

Gradio will provide a local URL and an optional public share link.

---
