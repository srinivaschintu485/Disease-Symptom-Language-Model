# Disease-Symptom-Language-Model

# Project Overview

This project trains a language model to understand and generate responses related to diseases and symptoms. The model is based on GPT-2 and can generate relevant text, potentially useful for applications like symptom checking or providing general information.

# Contents

The notebook includes:

Data Preparation: Loading and processing a dataset on diseases and symptoms.

Model Setup: Initializing and configuring GPT-2 for training on this dataset.

Training Process: Training the model over multiple epochs with specific batch settings, using PyTorch and Hugging Face’s Transformers library.

Evaluation: Validating the model to measure loss and check its generalization capability.

# Key Components

Data Loading: Loads a dataset of diseases and symptoms using the Hugging Face datasets library.

Data Preprocessing: Prepares text data for model compatibility, including tokenization and formatting.

Model Training: Runs a training loop with PyTorch, using GPU support when available.

Text Generation: Uses the trained model to generate text based on disease and symptom prompts.

# Requirements

Libraries: torch, transformers, pandas, tqdm, and datasets

Hardware: A compatible GPU is recommended for efficient training.
