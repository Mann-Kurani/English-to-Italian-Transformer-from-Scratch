# Transformer-based English-Italian Translator

## Overview
This project implements a Transformer model from scratch for English-to-Italian translation. The model is trained using the OPUS Books dataset and is inspired by the "Attention Is All You Need" paper. The implementation includes data preprocessing, tokenization, model training, and inference.

## Features
- Implements a Transformer model from scratch using PyTorch
- Supports English-to-Italian translation
- Utilizes the OPUS Books dataset for training
- Custom dataset handling and tokenization
- Training and validation with loss tracking and evaluation metrics

## Installation
### Prerequisites
Ensure you have Python installed, along with the required dependencies:
```bash
pip install torch datasets tokenizers torchmetrics tensorboard tqdm
```

## Project Structure
```
|-- config.py  # Configuration settings
|-- dataset.py  # Dataset preprocessing and tokenization
|-- model.py  # Transformer model implementation
|-- translation_en_it.py  # Training and evaluation
```

## References
- "Attention Is All You Need" - Vaswani et al.
- OPUS Books dataset
- PyTorch, Hugging Face datasets & tokenizers
- Umar Jamil Youtube video: https://youtu.be/ISNdQcPhsts
## License
This project is for educational purposes. Modify and use as needed!

