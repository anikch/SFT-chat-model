
# chat SFT
Allows for fine-tuning base models for chat purposes.

This script trains the norm and embed layers of the LLM, in addition to the LoRA adapters. This provides improved handling of beginning and end of sequence tokens - important for chat fine-tuning.

Check out huggingface.co/Trelis for OpenAssist datasets suitable for Llama style, Yi Style and Falcon Style datasets.

Notebooks:
- openassist_dataset_prep.ipynb = script for generating chat fine-tuning datasets
- Chat-fine-tuning.ipynb

## Getting Started with Data Preparation
```
pip install requirements.txt
```
Then activate the python virtual environment on a Mac with:
```
source dataEnv/bin/activate
```
> or 'dataEnv\Scripts\activate' on Windows.

Then install the required packages with:
```
pip install -r requirements.txt
```
