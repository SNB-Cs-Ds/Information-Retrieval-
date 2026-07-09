# Information Retrieval Project
## Simplified Unsupervised Machine Translation (NMT & PBSMT)

### Project Overview
This repository contains a simplified implementation of two unsupervised machine translation approaches developed as a course project for Information Retrieval.

The project reproduces the main ideas of the paper:

> Lample et al., "Phrase-Based & Neural Unsupervised Machine Translation" (2018)

The goal is not to exactly reproduce the original paper, but to build lightweight versions that can run on Google Colab using a small dataset.

---

## Repository Contents

- `NMT.ipynb`
  - Simplified Neural Machine Translation (NMT)
  - Shared embeddings
  - Small supervised warm-up
  - Denoising autoencoder
  - Iterative back-translation

- `PBSMT.ipynb`
  - Simplified Phrase-Based Statistical Machine Translation (PBSMT)
  - Word dictionary induction
  - Phrase table construction
  - Bigram Language Model
  - Beam-search decoder
  - Bidirectional back-translation

---

## Dataset

- Helsinki-NLP OPUS Books (English–Italian)
- Small subsets (50–500 sentence pairs) were used to keep the implementation lightweight.

---

## Requirements

- Python 3
- Google Colab
- PyTorch
- Transformers
- Datasets
- SacreBLEU
- Gensim
- NumPy
- Pandas

---

## Results

The project compares the simplified NMT and PBSMT models using BLEU score.

Although the scores are much lower than those reported in the original paper, both notebooks demonstrate the complete workflow of unsupervised machine translation on a toy dataset.

---

## Reference

Guillaume Lample, Myle Ott, Alexis Conneau, Ludovic Denoyer, Marc'Aurelio Ranzato.

**Phrase-Based & Neural Unsupervised Machine Translation**

ICLR 2018.

https://arxiv.org/abs/1804.07755

---

## Author

Nooshin Behrooz

M.Sc. Data Science

University of Trieste
