# SimplismartSubmission
Submission of Simplismart Assignment
Certainly! Below is how you can write the provided code explanation in a GitHub README format:

---

# Optimized MistralForCausalLM Inference

This repository contains an optimized script for inference using MistralForCausalLM-based language models. The script optimizes model loading and inference for efficient resource utilization and improved performance.

## Overview

The script loads a pretrained Mistral model from the specified Hugging Face model path and optimizes it using DeepSpeed for faster inference. It utilizes various DeepSpeed parameters such as `torch_dtype`, `offload_folder`, `trust_remote_code`, and `low_cpu_mem_usage` to improve memory usage, offload computations, and utilize available resources efficiently.

During inference, the script prompts the user for input, tokenizes it using the loaded tokenizer, and generates model output based on the user's prompt. It then decodes the generated output using the tokenizer and calculates performance metrics such as inference latency and throughput.

## Key Features

- Model Optimization with DeepSpeed: Efficient memory usage and resource utilization using DeepSpeed's optimization techniques.
- Model Parallelism: Utilizing multiple GPUs with specified model parallel size for efficient inference.
- Memory Optimization Parameters: Tuning DeepSpeed parameters to optimize memory usage and performance.
- Sharding: Loading the model in a sharded manner to reduce memory overhead during model loading.


## Dependencies

- torch
- transformers
- deepspeed

---
