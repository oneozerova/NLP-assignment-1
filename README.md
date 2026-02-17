# NLP Assignment 1: Byte-Pair Encoding Tokenizer

This is my solution for the NLP course assignment on Byte-Pair Encoding (BPE) tokenization.

## What is this project about?

In this assignment, I implemented a BPE tokenizer from scratch and tested it on the Brown corpus. The project has 3 main tasks:

1. **Data Preparation** - Load the Brown corpus and find the minimum vocabulary size that covers 90% of the words
2. **BPE Tokenizer Implementation** - Build a working BPE tokenizer with train and tokenize methods
3. **Analysis** - Train the tokenizer and calculate statistics like fertility and token length

## How to run this project

### Install requirements

First, install the needed packages:

```bash
pip install -r requirements.txt
```

### Run the notebook

Open the notebook and run all cells:

```bash
jupyter notebook "NatLanPro Assignment 1 (1).ipynb"
```

Or use JupyterLab:

```bash
jupyter lab
```

## What I learned

- How BPE tokenization works (merging character pairs based on frequency)
- Calculating vocabulary coverage from a corpus
- Working with the NLTK library and Brown corpus
- Zipf's law and why word frequency distributions have a long tail
- Understanding tokenizer metrics like fertility (tokens per word)

## Key findings

- The Brown corpus has **6545** unique words needed to cover 90% of all word occurrences
- My BPE tokenizer produces **~1.27 tokens per word** on average (fertility)
- Average sentence length after tokenization is **23 tokens**

## Files in this project

- `NatLanPro Assignment 1 (1).ipynb` - Main notebook with all code and results
- `requirements.txt` - Python packages needed to run this
- `README.md` - This file