# 6CS012 AI Coursework Portfolio

**Student:** Shrabya Paudel
**WLV ID:** 2414201
**Module:** Artificial Intelligence and Machine Learning
**Year:** 2026

## Contents

### Part II — Image Classification (CNN)
Notebook: `Image_Classification/2414201_ShrabyaPaudel_Code_Image_Classification.ipynb`

Image classification on the Intel Image Classification dataset (6 classes).
- Baseline CNN: 87.87% test accuracy
- Deeper CNN with regularization: 85.70%
- Transfer Learning (MobileNetV2): 92.07%

### Part III — Text Classification (RNN/LSTM)
Notebook: `Text_Classification/2414201_ShrabyaPaudel_Code_Text_Classification.ipynb`

Fake news detection on the True vs Fake News dataset (20,000 articles).
- Simple RNN: 53.90%
- LSTM trainable: 53.75%
- LSTM + GloVe (frozen): 94.13%

## How to Run

Both notebooks are designed for Google Colab with a T4 GPU. Datasets should be uploaded separately (not included in this repo due to size).
