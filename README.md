# AI Inference Performance Calculator

This interactive web application helps AI engineers and researchers estimate the inference performance of large language models based on hardware specs and model parameters. 

## Features
- Compute-limited and bandwidth-limited token throughput estimation
- First-token latency and per-token latency calculations
- Supports multiple GPUs in a cluster
- Adjustable precision: FP32, FP16, INT8, INT4, FP8
- KV cache and fractional weight streaming (f) calculations
- Memory bandwidth input per GPU
- Interactive, responsive, modern UI with animations
- Export results as JSON or copy to clipboard
- Step-by-step explanation of calculations

## Usage
Open `index.html` in any modern web browser. Input hardware and model parameters, click **Calculate**, and view results instantly.
