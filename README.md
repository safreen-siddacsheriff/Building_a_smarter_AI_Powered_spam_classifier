# Building_a_smarter_AI_Powered_spam_classifier

This project implements sentiment analysis using the RoBERTa model. The model is trained on a dataset containing text samples and corresponding sentiment labels.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [License](#license)

## Overview

The project utilizes the Hugging Face Transformers library and PyTorch to implement sentiment analysis. It involves loading a pre-trained RoBERTa model, tokenizing and encoding text sequences, defining a custom neural network architecture, and training the model on a labeled dataset.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Torch
- Transformers (Hugging Face)
- Scikit-learn

Install the required packages using:

```bash
pip install pandas numpy torch transformers scikit-learn
