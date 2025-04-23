# 🧠 Quote Generation Web App using DeepSeek R1

This project demonstrates a generative AI model fine-tuned to create meaningful and inspirational quotes based on user input text. The model is served through a simple and elegant **Streamlit** web interface.

---

## 🔍 Overview

Using the **DeepSeek R1 (7B)** large language model, we fine-tuned it on a curated dataset of quotes via **Supervised Fine-Tuning (SFT)**. The goal is to showcase how transfer learning can help adapt a pre-trained model for creative generation tasks.

Users can interact with the trained model through a web interface, enter a topic or phrase, and receive a uniquely generated quote in return.

---

## 🛠️ Tech Stack

- **Language Model**: [DeepSeek R1 (7B)](https://huggingface.co/deepseek-ai/deepseek-llm-7b-base)
- **Tokenizer**: DeepSeekTokenizer
- **Frameworks**:
  - [Hugging Face Transformers](https://huggingface.co/transformers/)
  - [PEFT (Parameter-Efficient Fine-Tuning)](https://github.com/huggingface/peft)
- **Web App**: [Streamlit](https://streamlit.io/)
- **Training Environment**: Google Colab 
- **Evaluation**: BLEU, ROUGE

---


