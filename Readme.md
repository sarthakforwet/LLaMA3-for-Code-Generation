# LLAMA3 AND UNSLOTH AI POWERED CODE GENERATOR

This project involves building a code generator using the `code-search-net` dataset from Hugging Face. The model used for training is the `llama-3-8b-bnb-4bit`, a quantized model that improves training speed by 5x. We also use Wandb for logging the model training process.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dependencies](#dependencies)
3. [Installation](#installation)

## Project Overview

This project focuses on creating an efficient code generation model. The key steps include installing necessary dependencies, importing required libraries, loading the model and dataset, training the model, and miscellaneous operations for optimizing the process.

## Dependencies

The project requires the following dependencies:
- Unsloth
- Xformers (Flash Attention)
- TRL
- PEFT
- Accelerate
- Bitsandbytes
- Triton (OpenAI's open-source library for GPU Programming)

## Installation

To install the necessary dependencies, run the following commands:

```bash
pip install "unsloth[colab-new] @ git+https://github.com/unslothai/unsloth.git"
pip install --no-deps xformers==0.0.25.post1 "trl<0.9.0" peft accelerate bitsandbytes
pip install triton
```