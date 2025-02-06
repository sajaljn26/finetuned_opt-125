# Fine-Tuning a Causal Language Model with Hugging Face Transformers

This repository contains a Python script for fine-tuning a causal language model using the Hugging Face `transformers` library. The script uses the `facebook/opt-125m` model and fine-tunes it on a custom dataset provided in a CSV file. The fine-tuned model is then saved and can be used for text generation.

## Requirements

To run this script, you need the following Python packages installed:

- `torch`
- `transformers`
- `datasets`

You can install these packages using pip:

```bash
pip install torch transformers datasets