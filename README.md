# Autoencoder-Based Image Segmentation on Hazelnut Dataset

## 🧠 Project Overview
This project implements an autoencoder neural network for **image segmentation** to detect anomalies in hazelnuts using the **MVTec AD dataset**. The goal is to reconstruct normal (non-defective) hazelnuts and identify differences when the model fails to reconstruct defective ones.

## ⚙️ How It Works
The autoencoder consists of:
- **Encoder**: Extracts features via Conv2D + MaxPooling.
- **Latent Space**: Compressed representation of the input.
- **Decoder**: Reconstructs the image using UpSampling + Conv2D.
- **Loss Function**: Binary Cross-Entropy.
- **Goal**: Reconstruct defect-free images; deviations in reconstruction suggest anomalies.
