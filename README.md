# Next Word Prediction with LSTM

This project is a Next Word Prediction system built using a Long Short-Term Memory (LSTM) neural network in PyTorch.
It was trained on the Medium Articles dataset for 100 epochs, reducing the loss from ~10,000 to ~800.

Given an input text sequence, the model predicts the most likely next word in real time, producing smooth, continuous text generation.

How It Works
Preprocessing: Tokenizes text, builds a vocabulary, converts words to indices, and pads sequences.

Model: Embedding layer → LSTM → Fully connected output layer.

Training: CrossEntropy loss with Adam optimizer.

Prediction: Takes an input sentence, predicts the next word, and appends it to generate text sequentially.

Demo

https://github.com/user-attachments/assets/6b86ee14-9833-4c57-a2b6-fd1c3b508447



Saving & Loading
The trained model, vocabulary, and settings are saved in checkpoint.pth for easy reuse.
