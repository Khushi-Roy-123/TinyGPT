# TinyGPT

A minimal, modular PyTorch implementation of a decoder-only Generative Pre-trained Transformer (GPT).

## Project Structure
- [transformer_blocks.py](file:///C:/Users/khush/Desktop/TINYGPT/transformer_blocks.py): Modular layers (SelfAttentionHead, MultiHeadAttention, FeedForward, Block).
- [demo.py](file:///C:/Users/khush/Desktop/TINYGPT/demo.py): Training and generation using word-level tokenization.
- [Tokenizer/tinygpt_tokenizer.py](file:///C:/Users/khush/Desktop/TINYGPT/Tokenizer/tinygpt_tokenizer.py): SentencePiece BPE subword tokenization.

## Prerequisites
```bash
pip install torch sentencepiece
```

## Running the Demos
- Word-level model: `python demo.py`
- Subword model: `python Tokenizer/tinygpt_tokenizer.py`

Set the environment variable KMP_DUPLICATE_LIB_OK=TRUE if you encounter OpenMP runtime library conflicts.
