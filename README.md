Natural Language Processing Coursework 2

This project is part of the Natural Language Processing CW2 assignment. The goal is to build a deep learning model using LSTM (Long Short-Term Memory) to classify text data for harmful content.

Files:

Natural Language Processing CW2.ipynb: Jupyter notebook with all the code.

TBO_4k_train.xlsx: Excel dataset with text and binary labels for harmful content.

Project Overview:

Data Loading & Preprocessing:

Loads text data from Excel.

Handles missing values and encodes labels.

Text Vectorization:

Tokenizes the text using Keras Tokenizer.

Pads sequences for consistent input length.

Model Architecture:

Sequential model with:

Embedding layer

Bidirectional LSTM

Dropout layers

Dense layers for output

Training & Evaluation:

Splits data into training and testing sets.

Trains the model and plots accuracy/loss graphs.

Requirements:

tensorflow

scikit-learn

pandas

numpy

matplotlib

openpyxl

You can install dependencies using: pip install -r requirements.txt

How to Run:

Upload the TBO_4k_train.xlsx dataset when prompted.

Run all cells in the Jupyter notebook.

Review training performance and model evaluation metrics.

Results: The model effectively classifies harmful vs. non-harmful content in text using deep learning, showcasing the strength of LSTM-based approaches in NLP tasks.

Acknowledgements:

Coventry University, MSc Computer Science - NLP Module

Tools used: TensorFlow, Keras, scikit-learn
