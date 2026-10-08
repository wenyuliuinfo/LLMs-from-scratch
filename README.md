# Build a Large Language Model (From Scratch) - Code Practice

This repository contains my personal code implementations and practice for the book *"Build a Large Language Model (From Scratch)"* by Sebastian Raschka. It is a hands-on, step-by-step journey through the fundamental components of a GPT-like Large Language Model, implemented from the ground up using PyTorch.

## 🎯 About This Repository

The goal of this repository is to serve as a personal learning log and a practical code reference for building an LLM from scratch. While based on the official book's code, this repo reflects my own coding style, experiments, and annotations as I work through each chapter.

It is not meant to replace the official repository but rather to document my learning process. You will find code for key components like the **BPE tokenizer**, **multi-head attention**, **GPT model architecture**, **pretraining**, and **finetuning**.

## 📂 Repository Structure

The content is organized by chapter, following the book's progression.

```
LLMs-from-scratch/
├── chap-02/    # Working with Text Data (Tokenization)
├── chap-03/    # Coding Attention Mechanisms
├── chap-04/    # Implementing a GPT Model from Scratch
├── chap-05/    # Pretraining on Unlabeled Data
├── chap-06/    # Finetuning for Text Classification
├── .gitignore
├── requirements.txt # Python dependencies
└── README.md
```

Each chapter folder contains the relevant Jupyter Notebooks or Python scripts for that stage of development.

## 🚀 Getting Started

### Prerequisites

To effectively use this repository, you should have:
- A strong foundation in Python programming.
- Basic familiarity with PyTorch (helpful but not mandatory).
- A computer with a reasonable amount of RAM (16GB+ recommended for larger models).

### Installation & Running the Code

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/wenyuliuinfo/LLMs-from-scratch.git
    cd LLMs-from-scratch
    ```

2. **Set up a Python environment:**
It's highly recommended to use a virtual environment.
    ```bash
    # Using venv (Python 3.9+)
    python -m venv .venv
    source .venv/bin/activate  # On Windows: .venv\Scripts\activate
    ```

3. **Install dependencies:**
All necessary packages are listed in requirements.txt.
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Notebooks:**
Navigate to a chapter folder and launch Jupyter Notebook.
    ```bash
    cd chap-02/01-main-chapter-code
    jupyter notebook
    ```


## 🧠 Key Topics Covered
This repository will guide you through the essential components of a modern LLM.

#### Chapter 2: Working with Text Data
- Byte Pair Encoding (BPE): Implementing a BPE tokenizer from scratch.

- Data Loading: Creating a PyTorch Dataset and DataLoader for language modeling.

- Embeddings: Understanding token and positional embeddings.

#### Chapter 3: Coding Attention Mechanisms
- Self-Attention: Implementing scaled dot-product attention with causal masking.

- Multi-Head Attention: Building the core attention module used in Transformer blocks.

- KV Cache: Implementing Key-Value caching for efficient text generation.

#### Chapter 4: Implementing a GPT Model from Scratch
- Layer Normalization: Implementing LayerNorm.

- GELU Activation: Implementing the GELU activation function.

- Feed-Forward Networks: Building the position-wise feed-forward network.

- Transformer Block: Assembling the complete Transformer decoder block.

- GPT Model: Building the full GPT architecture.

#### Chapter 5: Pretraining on Unlabeled Data
- Training Loop: Implementing the training loop for language modeling.

- Text Generation: Generating text with the trained model.

- Model Evaluation: Calculating perplexity and evaluating model performance.

#### Chapter 6: Finetuning for Text Classification
- Classification Head: Replacing the language modeling head with a classification head.

- Supervised Finetuning: Finetuning the pretrained model on a classification task (e.g., spam detection).

- Model Evaluation: Evaluating the finetuned classifier.


