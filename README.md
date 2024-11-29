# Catalog of Datasets for Ancient Latin Translation

This repository provides a curated collection of datasets designed to assist researchers, linguists, and developers in translating Ancient Latin texts. The datasets are aimed at improving machine learning models and natural language processing (NLP) applications focused on Latin, one of the foundational languages of classical literature, philosophy, and historical texts.

The goal of this repository is to centralize high-quality data resources that can be used for tasks such as Latin-to-English translation, syntactic analysis, and vocabulary enhancement. Whether you are working on developing translation tools, conducting linguistic studies, or exploring new AI techniques in classical languages, this catalog offers a valuable starting point.

Feel free to explore, contribute, or use these datasets for your projects, and don't hesitate to reach out for collaborations or inquiries.
## Datasets

# Latin-English Parallel Dataset

This dataset consists of **90,000 parallel sentences** in **Latin** and **English**. It is designed for machine learning tasks involving language translation, specifically for translating between Latin and Italian.

## Dataset Overview

- **Name**: `latin_english_parallel`
- **Size**: 90,000 rows
- **Languages**: Latin, English
- **Format**: Sentence pairs (Parallel corpus)
- **Source**: [Hugging Face Dataset]((https://huggingface.co/datasets/grosenthal/latin_english_parallel))

## Files in the Dataset

The dataset contains two columns:

- **latin**: The Latin text.
- **italian**: The corresponding Italian translation.

## Usage

You can load the dataset using Hugging Face's `datasets` library. Below is a basic example of how to load and use the dataset.

```python
from datasets import load_dataset

# Load the dataset
dataset = load_dataset("Dddixyy/latin_italian_parallel")

# Accessing the train split
train_data = dataset['train']

# Example: Display the first few rows
for example in train_data[:5]:
    print(f"Latin: {example['latin']}")
    print(f"Italian: {example['italian']}")
    print('-' * 80)



# Latin-Italian Parallel Dataset

This dataset consists of **5,000 parallel sentences** in **Latin** and **Italian**. It is designed for machine learning tasks involving language translation, specifically for translating between Latin and Italian.

## Dataset Overview

- **Name**: `latin_italian_parallel`
- **Size**: 5,000 rows
- **Languages**: Latin, Italian
- **Format**: Sentence pairs (Parallel corpus)
- **Source**: [Hugging Face Dataset](https://huggingface.co/datasets/Dddixyy/latin_italian_parallel)

## Files in the Dataset

The dataset contains two columns:

- **latin**: The Latin text.
- **italian**: The corresponding Italian translation.

## Usage

You can load the dataset using Hugging Face's `datasets` library. Below is a basic example of how to load and use the dataset.

```python
from datasets import load_dataset

# Load the dataset
dataset = load_dataset("Dddixyy/latin_italian_parallel")

# Accessing the train split
train_data = dataset['train']

# Example: Display the first few rows
for example in train_data[:5]:
    print(f"Latin: {example['latin']}")
    print(f"Italian: {example['italian']}")
    print('-' * 80)

