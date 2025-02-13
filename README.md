# Text Style Transfer: Informal to Formal

## Overview
This project aims to perform text style transfer, specifically converting informal text to formal text. It leverages the NUS Social Media Text Normalization and Translation Corpus. The repository explores three primary approaches:
1. A simple encoder-decoder model.
2. An encoder-decoder model with an attention mechanism.
3. Pre trained model (facebook bart-large)

## Getting Started

### Prerequisites
Ensure you have the following Python libraries installed:
- NumPy
- pandas
- Matplotlib
- seaborn
- TensorFlow
- NLTK (for `nltk.translate.bleu_score`)
- joblib
- scikit-learn
- NLPAug

### Data Preprocessing
Execute the `Data_Preprocessing.ipynb` notebook to prepare the data for training:
```bash
jupyter notebook Data_Preprocessing.ipynb
```

### Simple Encoder-Decoder Model
To run the simple encoder-decoder model:
```bash
jupyter notebook Simple_Encoder_Decoder.ipynb
```

### Encoder-Decoder Model with Attention Mechanism
For the attention mechanism-enhanced model:
```bash
jupyter notebook Final_Attention_Model.ipynb
```

### Using Pretrained Model Facebook Bart-large
For the pretrained model:
```bash
jupyter notebook Pre_Trained_Model.ipynb
```

## Streamlit Interface

This project includes a user-friendly interface built using Streamlit, a powerful framework for creating interactive web applications with Python. The interface allows users to interact with the model seamlessly and obtain results in real-time.

### Usage
To run the Streamlit interface, execute the following command in your terminal:

```bash
streamlit run app.py
```
