# PseudoCode to C++ Code Translator

## Overview
This project implements a Transformer-based Sequence-to-Sequence (Seq2Seq) model from scratch to convert pseudocode into C++ code. The model is trained without using any pretrained models, and a Streamlit web application is provided for deployment and interaction.

## Features
- Implements a Transformer-based Seq2Seq model for code translation.
- Trained from scratch without any pretrained models.
- Utilizes PyTorch for deep learning.
- Tokenization and preprocessing of pseudocode and C++ code.
- Deployment of the trained model using a Streamlit web application.

## Architecture
The model follows the Transformer-based sequence-to-sequence architecture with:
- **Encoder:** Converts pseudocode into embeddings and processes them using attention layers.
- **Decoder:** Generates C++ code by attending to the encoded representation and using recurrent layers.
- **Attention Mechanism:** Helps the model focus on relevant parts of the input sequence.

## Dataset
The dataset consists of paired pseudocode and C++ code samples. It has been preprocessed for training.

## Future Work
- Experimenting with different Transformer variants.
- Expanding dataset coverage.
- Fine-tuning for better accuracy.
- Deploying as an API for broader accessibility.


## Results
The model achieves promising results in translating structured pseudocode into valid C++ syntax. Improvements can be made through hyperparameter tuning and dataset expansion.
![PseudoCode to C++ Code Screenshot](https://github.com/Muradhameed921/PseudoCode-to-Cpp-Code-Translator/blob/main/P1.jpg)
![PseudoCode to C++ Code Screenshot](https://github.com/Muradhameed921/PseudoCode-to-Cpp-Code-Translator/blob/main/P2.jpg)

