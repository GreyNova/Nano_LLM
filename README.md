Nano_LLM
Nano_LLM is a lightweight, from-scratch implementation of a GPT-style transformer language model.
It’s designed for educational purposes, allowing step-by-step exploration of how GPT-like models are built and trained.


Overview

This project covers:
Tokenization and dataset preparation
Transformer architecture design
Training loop implementation
Text generation from a trained model
It’s implemented in Python + PyTorch with a focus on clean, modular code.


Features

Simple and readable code structure
Scales from small datasets to GPT-2 scale
Can be extended for fine-tuning on custom data
Runs on both CPU and GPU (CUDA supported)


Requirements

Python 3.9+
PyTorch
NumPy


Setup & Usage (Windows)

1️⃣ Install Dependencies
Open PowerShell in the project folder and run:
pip install -r requirements.txt

2️⃣ Train the Model
python train.py

3️⃣ Generate Text
python generate.py --prompt "Hello, I'm a language model,"


Future Improvements

Add fine-tuning support for conversational AI
Experiment with larger model configurations
Optimize training performance
