# 🤖 GPT-2 Based Customer Support Automation System (AMD)

This project demonstrates a GPT-2 fine-tuned language model designed to automate and enhance AMD's customer support. It enables the model to handle domain-specific customer queries efficiently, providing relevant, fluent, and context-aware responses.

## 🚀 Features

- Fine-tuned GPT-2 model on real AMD customer queries and support responses.
- Efficient domain adaptation using Hugging Face `Trainer` API.
- Automated Q&A chatbot system ready for integration.
- Complete training pipeline and inference interface provided.
- Lightweight and optimized for fast inference on GPU.

## 🏗️ Project Structure
- AMD-Customer Support Bot/
├── Final_Model/         # Final Model
├── venv/                      # Virtual environment folder (for dependencies)
├── data.json               # JSON Source File 
├── RunModel.ipynb   # Script to access the bot and use it
├── Pipeline/                # contains the complete pipeline of the model   


## Specifications
- LLM  Model
OpenAI’s GPT2
Model size-127 Million parameters
Language generation and text generation based

- Training Environment
Nvidia Tesla GPU T4
Platform: Kaggle Notebook
Accelerator: CUDA-enabled GPU training via PyTorch backend


