# ECG Signal Denoising Using Autoencoder

This project demonstrates a simple approach to denoise synthetic ECG signals using an Autoencoder neural network implemented in Python with TensorFlow.

---

## Project Overview

The objective is to generate a noisy ECG-like signal, preprocess it, and train an Autoencoder model to reconstruct a clean version of the signal. This example illustrates fundamental concepts of signal processing, neural network design, and denoising applications in biomedical signals.

---

## Key Features

- Synthetic ECG signal generation with added Gaussian noise
- Application of a Butterworth low-pass filter for preliminary noise reduction
- Segmentation of the signal into fixed-length overlapping windows
- Data normalization between 0 and 1 for stable training
- Design and training of a simple fully connected Autoencoder
- Visualization of original, noisy, and denoised ECG signals

---

## Requirements

- Python 3.x
- numpy
- matplotlib
- scipy
- scikit-learn
- tensorflow (version 2.x)

Install dependencies via pip:

```bash
pip install numpy matplotlib scipy scikit-learn tensorflow
