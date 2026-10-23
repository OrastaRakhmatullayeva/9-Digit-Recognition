<img width="1413" height="608" alt="Screenshot 2026-10-23 224557" src="https://github.com/user-attachments/assets/04dbaddc-8cd6-4988-99bf-f6a5411bf1f8" />
# Handwritten Digit Recognition with CNN

A Convolutional Neural Network that recognizes handwritten digits (0–9).

## What it does
1. Trains a CNN on the MNIST dataset (60,000 images).
2. Evaluates it on 10,000 unseen test images.
3. Predicts the digit from a new image I draw myself.

## Results
- Test accuracy: **99.09%**
- Custom hand-drawn "2" → predicted **2** with 97.4% confidence

## Model
- 2 × Conv2D + MaxPooling layers
- Dense(64) + Softmax(10)
- Optimizer: Adam, 5 epochs

## Tech stack
Python, TensorFlow/Keras, NumPy, Pillow, Matplotlib

## How to run
1. Open the notebook in Google Colab.
2. Run all cells to train the model.
3. Upload your own digit image and run the prediction cell.
